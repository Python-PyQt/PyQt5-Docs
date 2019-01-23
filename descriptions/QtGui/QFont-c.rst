.. sip:class-description::
    :status: todo
    :brief: Specifies a font used for drawing text
    :digest: e8c4feae4e66936f5fd59bf3c13f2983

The :sip:ref:`~PyQt5.QtGui.QFont` class specifies a font used for drawing text.

When you create a :sip:ref:`~PyQt5.QtGui.QFont` object you specify various attributes that you want the font to have. Qt will use the font with the specified attributes, or if no matching font exists, Qt will use the closest matching installed font. The attributes of the font that is actually used are retrievable from a :sip:ref:`~PyQt5.QtGui.QFontInfo` object. If the window system provides an exact match :sip:ref:`~PyQt5.QtGui.QFont.exactMatch` returns ``true``. Use :sip:ref:`~PyQt5.QtGui.QFontMetrics` to get measurements, e.g. the pixel length of a string using :sip:ref:`~PyQt5.QtGui.QFontMetrics.width`.

Note that a :sip:ref:`~PyQt5.QtGui.QGuiApplication` instance must exist before a :sip:ref:`~PyQt5.QtGui.QFont` can be used. You can set the application's default font with :sip:ref:`~PyQt5.QtGui.QGuiApplication.setFont`.

If a chosen font does not include all the characters that need to be displayed, :sip:ref:`~PyQt5.QtGui.QFont` will try to find the characters in the nearest equivalent fonts. When a :sip:ref:`~PyQt5.QtGui.QPainter` draws a character from a font the :sip:ref:`~PyQt5.QtGui.QFont` will report whether or not it has the character; if it does not, :sip:ref:`~PyQt5.QtGui.QPainter` will draw an unfilled square.

Create QFonts like this:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qfont.py
    :lines: 54-55

The attributes set in the constructor can also be set later, e.g. :sip:ref:`~PyQt5.QtGui.QFont.setFamily`, :sip:ref:`~PyQt5.QtGui.QFont.setPointSize`, :sip:ref:`~PyQt5.QtGui.QFont.setPointSizeF`, :sip:ref:`~PyQt5.QtGui.QFont.setWeight` and :sip:ref:`~PyQt5.QtGui.QFont.setItalic`. The remaining attributes must be set after contstruction, e.g. :sip:ref:`~PyQt5.QtGui.QFont.setBold`, :sip:ref:`~PyQt5.QtGui.QFont.setUnderline`, :sip:ref:`~PyQt5.QtGui.QFont.setOverline`, :sip:ref:`~PyQt5.QtGui.QFont.setStrikeOut` and :sip:ref:`~PyQt5.QtGui.QFont.setFixedPitch`. :sip:ref:`~PyQt5.QtGui.QFontInfo` objects should be created *after* the font's attributes have been set. A :sip:ref:`~PyQt5.QtGui.QFontInfo` object will not change, even if you change the font's attributes. The corresponding "get" functions, e.g. :sip:ref:`~PyQt5.QtGui.QFont.family`, :sip:ref:`~PyQt5.QtGui.QFont.pointSize`, etc., return the values that were set, even though the values used may differ. The actual values are available from a :sip:ref:`~PyQt5.QtGui.QFontInfo` object.

If the requested font family is unavailable you can influence the font matching algorithm by choosing a particular :sip:ref:`~PyQt5.QtGui.QFont.StyleHint` and :sip:ref:`~PyQt5.QtGui.QFont.StyleStrategy` with :sip:ref:`~PyQt5.QtGui.QFont.setStyleHint`. The default family (corresponding to the current style hint) is returned by :sip:ref:`~PyQt5.QtGui.QFont.defaultFamily`.

The font-matching algorithm has a :sip:ref:`~PyQt5.QtGui.QFont.lastResortFamily` and :sip:ref:`~PyQt5.QtGui.QFont.lastResortFont` in cases where a suitable match cannot be found. You can provide substitutions for font family names using :sip:ref:`~PyQt5.QtGui.QFont.insertSubstitution` and :sip:ref:`~PyQt5.QtGui.QFont.insertSubstitutions`. Substitutions can be removed with removeSubstitutions(). Use :sip:ref:`~PyQt5.QtGui.QFont.substitute` to retrieve a family's first substitute, or the family name itself if it has no substitutes. Use :sip:ref:`~PyQt5.QtGui.QFont.substitutes` to retrieve a list of a family's substitutes (which may be empty).

Every :sip:ref:`~PyQt5.QtGui.QFont` has a :sip:ref:`~PyQt5.QtGui.QFont.key` which you can use, for example, as the key in a cache or dictionary. If you want to store a user's font preferences you could use :sip:ref:`~PyQt5.QtCore.QSettings`, writing the font information with :sip:ref:`~PyQt5.QtGui.QFont.toString` and reading it back with :sip:ref:`~PyQt5.QtGui.QFont.fromString`. The operator<<() and operator>>() functions are also available, but they work on a data stream.

It is possible to set the height of characters shown on the screen to a specified number of pixels with :sip:ref:`~PyQt5.QtGui.QFont.setPixelSize`; however using :sip:ref:`~PyQt5.QtGui.QFont.setPointSize` has a similar effect and provides device independence.

Loading fonts can be expensive, especially on X11. :sip:ref:`~PyQt5.QtGui.QFont` contains extensive optimizations to make the copying of :sip:ref:`~PyQt5.QtGui.QFont` objects fast, and to cache the results of the slow window system functions it depends upon.

.. _qfont-fontmatching:

The font matching algorithm works as follows:

#. The specified font family is searched for.

#. If not found, the :sip:ref:`~PyQt5.QtGui.QFont.styleHint` is used to select a replacement family.

#. Each replacement font family is searched for.

#. If none of these are found or there was no :sip:ref:`~PyQt5.QtGui.QFont.styleHint`, "helvetica" will be searched for.

#. If "helvetica" isn't found Qt will try the :sip:ref:`~PyQt5.QtGui.QFont.lastResortFamily`.

#. If the :sip:ref:`~PyQt5.QtGui.QFont.lastResortFamily` isn't found Qt will try the :sip:ref:`~PyQt5.QtGui.QFont.lastResortFont` which will always return a name of some kind.

Note that the actual font matching algorithm varies from platform to platform.

In Windows a request for the "Courier" font is automatically changed to "Courier New", an improved version of Courier that allows for smooth scaling. The older "Courier" bitmap font can be selected by setting the :sip:ref:`~PyQt5.QtGui.QFont.StyleStrategy.PreferBitmap` style strategy (see :sip:ref:`~PyQt5.QtGui.QFont.setStyleStrategy`).

Once a font is found, the remaining attributes are matched in order of priority:

#. :sip:ref:`~PyQt5.QtGui.QFont.fixedPitch`

#. :sip:ref:`~PyQt5.QtGui.QFont.pointSize` (see below)

#. :sip:ref:`~PyQt5.QtGui.QFont.weight`

#. :sip:ref:`~PyQt5.QtGui.QFont.style`

If you have a font which matches on family, even if none of the other attributes match, this font will be chosen in preference to a font which doesn't match on family but which does match on the other attributes. This is because font family is the dominant search criteria.

The point size is defined to match if it is within 20% of the requested point size. When several fonts match and are only distinguished by point size, the font with the closest point size to the one requested will be chosen.

The actual family, font size, weight and other font attributes used for drawing text will depend on what's available for the chosen family under the window system. A :sip:ref:`~PyQt5.QtGui.QFontInfo` object can be used to determine the actual values used for drawing the text.

Examples:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qfont.py
    :lines: 60-60

If you had both an Adobe and a Cronyx Helvetica, you might get either.

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qfont.py
    :lines: 65-65

You can specify the foundry you want in the family name. The font f in the above example will be set to "Helvetica [Cronyx]".

To determine the attributes of the font actually used in the window system, use a :sip:ref:`~PyQt5.QtGui.QFontInfo` object, e.g.

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qfont.py
    :lines: 70-71

To find out font metrics use a :sip:ref:`~PyQt5.QtGui.QFontMetrics` object, e.g.

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qfont.py
    :lines: 76-78

For more general information on fonts, see the `comp.fonts FAQ <https://doc.qt.io/qt-5/http://nwalsh.com/comp.fonts/FAQ/>`_. Information on encodings can be found from `Roman Czyborra's <https://doc.qt.io/qt-5/http://czyborra.com/>`_ page.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontMetrics`, :sip:ref:`~PyQt5.QtGui.QFontInfo`, :sip:ref:`~PyQt5.QtGui.QFontDatabase`, `Character Map Example <https://doc.qt.io/qt-5/qtwidgets-widgets-charactermap-example.html>`_.
