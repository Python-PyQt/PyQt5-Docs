.. sip:method-description::
    :status: todo
    :pysig: 7c1a62ac509e2527a42effe56c9b2ccd
    :realsig: (const QRectF&,qreal,qreal,Qt::SizeMode)
    :digest: 7a225c871a5078fa1d71ad0469f14706

Draws the given rectangle *rect* with rounded corners.

The *xRadius* and *yRadius* arguments specify the radii of the ellipses defining the corners of the rounded rectangle. When *mode* is :sip:ref:`~PyQt5.QtCore.Qt.SizeMode.RelativeSize`, *xRadius* and *yRadius* are specified in percentage of half the rectangle's width and height respectively, and should be in the range 0.0 to 100.0.

A filled rectangle has a size of rect.size(). A stroked rectangle has a size of rect.size() plus the pen width.

+--------------------------------+-----------------------------------------------------------------------------------------------------+
| |image-qpainter-roundrect-png| | .. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_painting_qpainter.py |
|                                |     :lines: 133-136                                                                                 |
+--------------------------------+-----------------------------------------------------------------------------------------------------+

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter.drawRect`, :sip:ref:`~PyQt5.QtGui.QPen`.

.. |image-qpainter-roundrect-png| image:: ../../../images/qpainter-roundrect.png
