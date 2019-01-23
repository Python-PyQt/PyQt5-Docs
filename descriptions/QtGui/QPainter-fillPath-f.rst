.. sip:method-description::
    :status: todo
    :pysig: a04b4720cce030af8bea99eb45661210
    :realsig: (const QPainterPath&,const QBrush&)
    :digest: 2c6ca5615da8aba2111307b1bc1d75b7

Fills the given *path* using the given *brush*. The outline is not drawn.

Alternatively, you can specify a :sip:ref:`~PyQt5.QtGui.QColor` instead of a :sip:ref:`~PyQt5.QtGui.QBrush`; the :sip:ref:`~PyQt5.QtGui.QBrush` constructor (taking a :sip:ref:`~PyQt5.QtGui.QColor` argument) will automatically create a solid pattern brush.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter.drawPath`.
