:orphan:

.. sip:class:: PyQt5.QtGui.QPainterPath
    :description: QtGui/QPainterPath-c.rst

    .. sip:enum:: PyQt5.QtGui.QPainterPath.ElementType
        :description: QtGui/QPainterPath-ElementType-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QPainterPath.ElementType.CurveToDataElement
            :description: QtGui/QPainterPath-ElementType-CurveToDataElement-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QPainterPath.ElementType.CurveToElement
            :description: QtGui/QPainterPath-ElementType-CurveToElement-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QPainterPath.ElementType.LineToElement
            :description: QtGui/QPainterPath-ElementType-LineToElement-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QPainterPath.ElementType.MoveToElement
            :description: QtGui/QPainterPath-ElementType-MoveToElement-v.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__init__
        :description: QtGui/QPainterPath-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QPainterPath-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__init__-f-2.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__add__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__add__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addEllipse
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtGui/QPainterPath-addEllipse-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addEllipse
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            float
            float
        :description: QtGui/QPainterPath-addEllipse-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addEllipse
        :args:
            float
            float
            float
            float
        :description: QtGui/QPainterPath-addEllipse-f-2.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addPath
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-addPath-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addPolygon
        :args:
            :sip:ref:`~PyQt5.QtGui.QPolygonF`
        :description: QtGui/QPainterPath-addPolygon-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtGui/QPainterPath-addRect-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addRect
        :args:
            float
            float
            float
            float
        :description: QtGui/QPainterPath-addRect-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addRegion
        :args:
            :sip:ref:`~PyQt5.QtGui.QRegion`
        :description: QtGui/QPainterPath-addRegion-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addRoundedRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            float
            float
            mode: :sip:ref:`~PyQt5.QtCore.Qt.SizeMode` = :sip:ref:`~PyQt5.QtCore.Qt.SizeMode.AbsoluteSize`
        :description: QtGui/QPainterPath-addRoundedRect-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addRoundedRect
        :args:
            float
            float
            float
            float
            float
            float
            mode: :sip:ref:`~PyQt5.QtCore.Qt.SizeMode` = :sip:ref:`~PyQt5.QtCore.Qt.SizeMode.AbsoluteSize`
        :description: QtGui/QPainterPath-addRoundedRect-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addText
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            :sip:ref:`~PyQt5.QtGui.QFont`
            str
        :description: QtGui/QPainterPath-addText-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.addText
        :args:
            float
            float
            :sip:ref:`~PyQt5.QtGui.QFont`
            str
        :description: QtGui/QPainterPath-addText-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__and__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__and__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.angleAtPercent
        :args:
            float
        :returns:
            float
        :description: QtGui/QPainterPath-angleAtPercent-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.arcMoveTo
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            float
        :description: QtGui/QPainterPath-arcMoveTo-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.arcMoveTo
        :args:
            float
            float
            float
            float
            float
        :description: QtGui/QPainterPath-arcMoveTo-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.arcTo
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            float
            float
        :description: QtGui/QPainterPath-arcTo-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.arcTo
        :args:
            float
            float
            float
            float
            float
            float
        :description: QtGui/QPainterPath-arcTo-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.boundingRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtGui/QPainterPath-boundingRect-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.closeSubpath
        :description: QtGui/QPainterPath-closeSubpath-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.connectPath
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-connectPath-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.contains
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :returns:
            bool
        :description: QtGui/QPainterPath-contains-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.contains
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :returns:
            bool
        :description: QtGui/QPainterPath-contains-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.contains
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            bool
        :description: QtGui/QPainterPath-contains-f-2.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.controlPointRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtGui/QPainterPath-controlPointRect-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.cubicTo
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QPainterPath-cubicTo-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.cubicTo
        :args:
            float
            float
            float
            float
            float
            float
        :description: QtGui/QPainterPath-cubicTo-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.currentPosition
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtGui/QPainterPath-currentPosition-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.elementAt
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath.Element`
        :description: QtGui/QPainterPath-elementAt-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.elementCount
        :returns:
            int
        :description: QtGui/QPainterPath-elementCount-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__eq__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            bool
        :description: QtGui/QPainterPath-__eq__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.fillRule
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.FillRule`
        :description: QtGui/QPainterPath-fillRule-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__iadd__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__iadd__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__iand__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__iand__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.intersected
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-intersected-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.intersects
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :returns:
            bool
        :description: QtGui/QPainterPath-intersects-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.intersects
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            bool
        :description: QtGui/QPainterPath-intersects-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__ior__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__ior__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.isEmpty
        :returns:
            bool
        :description: QtGui/QPainterPath-isEmpty-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__isub__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__isub__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.length
        :returns:
            float
        :description: QtGui/QPainterPath-length-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.lineTo
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QPainterPath-lineTo-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.lineTo
        :args:
            float
            float
        :description: QtGui/QPainterPath-lineTo-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.moveTo
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QPainterPath-moveTo-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.moveTo
        :args:
            float
            float
        :description: QtGui/QPainterPath-moveTo-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__mul__
        :args:
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__mul__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__ne__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            bool
        :description: QtGui/QPainterPath-__ne__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__or__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__or__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.percentAtLength
        :args:
            float
        :returns:
            float
        :description: QtGui/QPainterPath-percentAtLength-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.pointAtPercent
        :args:
            float
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtGui/QPainterPath-pointAtPercent-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.quadTo
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QPainterPath-quadTo-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.quadTo
        :args:
            float
            float
            float
            float
        :description: QtGui/QPainterPath-quadTo-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.setElementPositionAt
        :args:
            int
            float
            float
        :description: QtGui/QPainterPath-setElementPositionAt-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.setFillRule
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.FillRule`
        :description: QtGui/QPainterPath-setFillRule-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.simplified
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-simplified-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.slopeAtPercent
        :args:
            float
        :returns:
            float
        :description: QtGui/QPainterPath-slopeAtPercent-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.__sub__
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-__sub__-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.subtracted
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-subtracted-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.swap
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-swap-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.toFillPolygon
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygonF`
        :description: QtGui/QPainterPath-toFillPolygon-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.toFillPolygon
        :args:
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygonF`
        :description: QtGui/QPainterPath-toFillPolygon-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.toFillPolygons
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QPolygonF`]
        :description: QtGui/QPainterPath-toFillPolygons-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.toFillPolygons
        :args:
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QPolygonF`]
        :description: QtGui/QPainterPath-toFillPolygons-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.toReversed
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-toReversed-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.toSubpathPolygons
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QPolygonF`]
        :description: QtGui/QPainterPath-toSubpathPolygons-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.toSubpathPolygons
        :args:
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QPolygonF`]
        :description: QtGui/QPainterPath-toSubpathPolygons-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.translate
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QPainterPath-translate-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.translate
        :args:
            float
            float
        :description: QtGui/QPainterPath-translate-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.translated
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-translated-f.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.translated
        :args:
            float
            float
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-translated-f-1.rst

    .. sip:method:: PyQt5.QtGui.QPainterPath.united
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtGui/QPainterPath-united-f.rst
