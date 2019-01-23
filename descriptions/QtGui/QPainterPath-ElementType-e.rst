.. sip:enum-description::
    :status: todo
    :digest: a5504aa66e1ea0305a9155dd9e6fe8ad

This enum describes the types of elements used to connect vertices in subpaths.

Note that elements added as closed subpaths using the :sip:ref:`~PyQt5.QtGui.QPainterPath.addEllipse`, :sip:ref:`~PyQt5.QtGui.QPainterPath.addPath`, :sip:ref:`~PyQt5.QtGui.QPainterPath.addPolygon`, :sip:ref:`~PyQt5.QtGui.QPainterPath.addRect`, :sip:ref:`~PyQt5.QtGui.QPainterPath.addRegion` and :sip:ref:`~PyQt5.QtGui.QPainterPath.addText` convenience functions, is actually added to the path as a collection of separate elements using the :sip:ref:`~PyQt5.QtGui.QPainterPath.moveTo`, :sip:ref:`~PyQt5.QtGui.QPainterPath.lineTo` and :sip:ref:`~PyQt5.QtGui.QPainterPath.cubicTo` functions.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainterPath.elementAt`, :sip:ref:`~PyQt5.QtGui.QPainterPath.elementCount`.
