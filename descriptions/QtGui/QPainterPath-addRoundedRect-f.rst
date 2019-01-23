.. sip:method-description::
    :status: todo
    :pysig: 7c1a62ac509e2527a42effe56c9b2ccd
    :realsig: (const QRectF&,qreal,qreal,Qt::SizeMode)
    :digest: 36b9557756d4d77f1320ca4fa9483683

Adds the given rectangle *rect* with rounded corners to the path.

The *xRadius* and *yRadius* arguments specify the radii of the ellipses defining the corners of the rounded rectangle. When *mode* is :sip:ref:`~PyQt5.QtCore.Qt.SizeMode.RelativeSize`, *xRadius* and *yRadius* are specified in percentage of half the rectangle's width and height respectively, and should be in the range 0.0 to 100.0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainterPath.addRect`.
