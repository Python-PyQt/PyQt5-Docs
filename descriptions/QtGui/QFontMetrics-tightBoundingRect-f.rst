.. sip:method-description::
    :status: todo
    :pysig: 0a25c2208ece1ab13b0cdb04eea33d25
    :realsig: (const QString&) const
    :digest: 8bbd153ded5d1bdc356fa099fb2d1072

Returns a tight bounding rectangle around the characters in the string specified by *text*. The bounding rectangle always covers at least the set of pixels the text would cover if drawn at (0, 0).

Note that the bounding rectangle may extend to the left of (0, 0), e.g. for italicized fonts, and that the width of the returned rectangle might be different than what the :sip:ref:`~PyQt5.QtGui.QFontMetrics.width` method returns.

If you want to know the advance width of the string (to lay out a set of strings next to each other), use horizontalAdvance() instead.

Newline characters are processed as normal characters, *not* as linebreaks.

**Warning:** Calling this method is very slow on Windows.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontMetrics.width`, :sip:ref:`~PyQt5.QtGui.QFontMetrics.height`, :sip:ref:`~PyQt5.QtGui.QFontMetrics.boundingRect`.
