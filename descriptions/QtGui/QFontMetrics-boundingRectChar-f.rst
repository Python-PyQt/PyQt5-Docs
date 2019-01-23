.. sip:method-description::
    :status: todo
    :pysig: 0a25c2208ece1ab13b0cdb04eea33d25
    :realname: QFontMetrics::boundingRect
    :realsig: (QChar) const
    :digest: 9f88234b630992b749ca9c5b7dce6c0e

Returns the rectangle that is covered by ink if character *ch* were to be drawn at the origin of the coordinate system.

Note that the bounding rectangle may extend to the left of (0, 0) (e.g., for italicized fonts), and that the text output may cover *all* pixels in the bounding rectangle. For a space character the rectangle will usually be empty.

Note that the rectangle usually extends both above and below the base line.

**Warning:** The width of the returned rectangle is not the advance width of the character. Use (const QString &) or horizontalAdvance() instead.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontMetrics.width`.
