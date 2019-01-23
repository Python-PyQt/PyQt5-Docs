.. sip:method-description::
    :status: todo
    :pysig: ea6ac2d80611fa5cf4211e0304bb0d9c
    :realsig: (const QPoint*,int)
    :digest: 7bad79f82312d9012747c0e6f351d40d

Draws the first *pointCount* points in the buffer *points*

The default implementation converts the first *pointCount* QPoints in *points* to QPointFs and calls the floating point version of :sip:ref:`~PyQt5.QtGui.QPaintEngine.drawPoints`.
