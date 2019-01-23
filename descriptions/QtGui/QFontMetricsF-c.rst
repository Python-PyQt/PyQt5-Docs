.. sip:class-description::
    :status: todo
    :brief: Font metrics information
    :digest: 62fbb2b96047522e5260ea29fd151104

The :sip:ref:`~PyQt5.QtGui.QFontMetricsF` class provides font metrics information.

:sip:ref:`~PyQt5.QtGui.QFontMetricsF` functions calculate the size of characters and strings for a given font. You can construct a :sip:ref:`~PyQt5.QtGui.QFontMetricsF` object with an existing :sip:ref:`~PyQt5.QtGui.QFont` to obtain metrics for that font. If the font is changed later, the font metrics object is *not* updated.

Once created, the object provides functions to access the individual metrics of the font, its characters, and for strings rendered in the font.

There are several functions that operate on the font: :sip:ref:`~PyQt5.QtGui.QFontMetricsF.ascent`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.descent`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.height`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.leading` and :sip:ref:`~PyQt5.QtGui.QFontMetricsF.lineSpacing` return the basic size properties of the font. The :sip:ref:`~PyQt5.QtGui.QFontMetricsF.underlinePos`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.overlinePos`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.strikeOutPos` and :sip:ref:`~PyQt5.QtGui.QFontMetricsF.lineWidth` functions, return the properties of the line that underlines, overlines or strikes out the characters. These functions are all fast.

There are also some functions that operate on the set of glyphs in the font: :sip:ref:`~PyQt5.QtGui.QFontMetricsF.minLeftBearing`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.minRightBearing` and :sip:ref:`~PyQt5.QtGui.QFontMetricsF.maxWidth`. These are by necessity slow, and we recommend avoiding them if possible.

For each character, you can get its :sip:ref:`~PyQt5.QtGui.QFontMetricsF.width`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.leftBearing` and :sip:ref:`~PyQt5.QtGui.QFontMetricsF.rightBearing` and find out whether it is in the font using :sip:ref:`~PyQt5.QtGui.QFontMetricsF.inFont`. You can also treat the character as a string, and use the string functions on it.

The string functions include :sip:ref:`~PyQt5.QtGui.QFontMetricsF.width`, to return the width of a string in pixels (or points, for a printer), :sip:ref:`~PyQt5.QtGui.QFontMetricsF.boundingRect`, to return a rectangle large enough to contain the rendered string, and :sip:ref:`~PyQt5.QtGui.QFontMetricsF.size`, to return the size of that rectangle.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qfontmetrics.py
    :lines: 62-65

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFont`, :sip:ref:`~PyQt5.QtGui.QFontInfo`, :sip:ref:`~PyQt5.QtGui.QFontDatabase`.
