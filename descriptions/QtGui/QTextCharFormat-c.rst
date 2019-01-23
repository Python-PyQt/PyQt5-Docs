.. sip:class-description::
    :status: todo
    :brief: Formatting information for characters in a QTextDocument
    :digest: d3972dcd5407b6b628287e9a286d347d

The :sip:ref:`~PyQt5.QtGui.QTextCharFormat` class provides formatting information for characters in a :sip:ref:`~PyQt5.QtGui.QTextDocument`.

The character format of text in a document specifies the visual properties of the text, as well as information about its role in a hypertext document.

The font used can be set by supplying a font to the :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFont` function, and each aspect of its appearance can be adjusted to give the desired effect. :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontFamily` and :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontPointSize` define the font's family (e.g. Times) and printed size; :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontWeight` and :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontItalic` provide control over the style of the font. :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontUnderline`, :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontOverline`, :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontStrikeOut`, and :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setFontFixedPitch` provide additional effects for text.

The color is set with setForeground(). If the text is intended to be used as an anchor (for hyperlinks), this can be enabled with :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setAnchor`. The :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setAnchorHref` and :sip:ref:`~PyQt5.QtGui.QTextCharFormat.setAnchorNames` functions are used to specify the information about the hyperlink's destination and the anchor's name.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextFormat`, :sip:ref:`~PyQt5.QtGui.QTextBlockFormat`, :sip:ref:`~PyQt5.QtGui.QTextTableFormat`, :sip:ref:`~PyQt5.QtGui.QTextListFormat`.
