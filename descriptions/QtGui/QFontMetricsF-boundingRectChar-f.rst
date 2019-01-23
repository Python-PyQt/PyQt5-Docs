.. sip:method-description::
    :status: todo
    :pysig: dc2404455d3722770039a142ccc1cf8b
    :realname: QFontMetricsF::boundingRect
    :realsig: (QChar) const
    :digest: 0817eeb2941b71b980ae83199af462fe

Returns the bounding rectangle of the character *ch* relative to the left-most point on the base line.

Note that the bounding rectangle may extend to the left of (0, 0), e.g. for italicized fonts, and that the text output may cover *all* pixels in the bounding rectangle.

Note that the rectangle usually extends both above and below the base line.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontMetricsF.width`.
