.. sip:method-description::
    :status: todo
    :pysig: fc1d571b15a5b849e33e2e5dd4ca1b66
    :realsig: (const QPixmap&)
    :digest: d84f15f110a6d61a0046874779835e80

Sets the brush pixmap to *pixmap*. The style is set to :sip:ref:`~PyQt5.QtCore.Qt.BrushStyle.TexturePattern`.

The current brush color will only have an effect for monochrome pixmaps, i.e. for :sip:ref:`~PyQt5.QtGui.QPixmap.depth` == 1 (\ :sip:ref:`~PyQt5.QtGui.QBitmap`).

.. seealso:: :sip:ref:`~PyQt5.QtGui.QBrush.texture`.
