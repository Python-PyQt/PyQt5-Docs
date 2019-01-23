.. sip:method-description::
    :status: todo
    :pysig: dc2404455d3722770039a142ccc1cf8b
    :realsig: (const QString&) const
    :digest: 881df04f8a34b13a3e01e9dc1b9510b4

Returns the bounding rectangle of the characters in the string specified by *text*. The bounding rectangle always covers at least the set of pixels the text would cover if drawn at (0, 0).

Note that the bounding rectangle may extend to the left of (0, 0), e.g. for italicized fonts, and that the width of the returned rectangle might be different than what the :sip:ref:`~PyQt5.QtGui.QFontMetricsF.width` method returns.

If you want to know the advance width of the string (to lay out a set of strings next to each other), use horizontalAdvance() instead.

Newline characters are processed as normal characters, *not* as linebreaks.

The height of the bounding rectangle is at least as large as the value returned :sip:ref:`~PyQt5.QtGui.QFontMetricsF.height`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontMetricsF.width`, :sip:ref:`~PyQt5.QtGui.QFontMetricsF.height`, :sip:ref:`~PyQt5.QtGui.QPainter.boundingRect`.
