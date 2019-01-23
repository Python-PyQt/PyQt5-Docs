:orphan:

.. sip:class:: PyQt5.QtChart.QLegend
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QGraphicsWidget`
    :description: QtChart/QLegend-c.rst

    .. sip:enum:: PyQt5.QtChart.QLegend.MarkerShape
        :description: QtChart/QLegend-MarkerShape-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QLegend.MarkerShape.MarkerShapeCircle
            :description: QtChart/QLegend-MarkerShape-MarkerShapeCircle-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QLegend.MarkerShape.MarkerShapeDefault
            :description: QtChart/QLegend-MarkerShape-MarkerShapeDefault-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QLegend.MarkerShape.MarkerShapeFromSeries
            :description: QtChart/QLegend-MarkerShape-MarkerShapeFromSeries-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QLegend.MarkerShape.MarkerShapeRectangle
            :description: QtChart/QLegend-MarkerShape-MarkerShapeRectangle-v.rst

    .. sip:method:: PyQt5.QtChart.QLegend.alignment
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.Alignment`
        :description: QtChart/QLegend-alignment-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.attachToChart
        :description: QtChart/QLegend-attachToChart-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.borderColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtChart/QLegend-borderColor-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.brush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtChart/QLegend-brush-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.color
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtChart/QLegend-color-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.detachFromChart
        :description: QtChart/QLegend-detachFromChart-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.font
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtChart/QLegend-font-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.hideEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QHideEvent`
        :description: QtChart/QLegend-hideEvent-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.isAttachedToChart
        :returns:
            bool
        :description: QtChart/QLegend-isAttachedToChart-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.isBackgroundVisible
        :returns:
            bool
        :description: QtChart/QLegend-isBackgroundVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.labelBrush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtChart/QLegend-labelBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.labelColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtChart/QLegend-labelColor-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.markers
        :args:
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :returns:
            List[:sip:ref:`~PyQt5.QtChart.QLegendMarker`]
        :description: QtChart/QLegend-markers-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.markerShape
        :returns:
            :sip:ref:`~PyQt5.QtChart.QLegend.MarkerShape`
        :description: QtChart/QLegend-markerShape-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.paint
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionGraphicsItem`
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtChart/QLegend-paint-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.pen
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPen`
        :description: QtChart/QLegend-pen-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.reverseMarkers
        :returns:
            bool
        :description: QtChart/QLegend-reverseMarkers-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setAlignment
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :description: QtChart/QLegend-setAlignment-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setBackgroundVisible
        :args:
            visible: bool = True
        :description: QtChart/QLegend-setBackgroundVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setBorderColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-setBorderColor-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-setBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-setColor-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setFont
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtChart/QLegend-setFont-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setLabelBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-setLabelBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setLabelColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-setLabelColor-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setMarkerShape
        :args:
            :sip:ref:`~PyQt5.QtChart.QLegend.MarkerShape`
        :description: QtChart/QLegend-setMarkerShape-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setPen
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QPen`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-setPen-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setReverseMarkers
        :args:
            reverseMarkers: bool = True
        :description: QtChart/QLegend-setReverseMarkers-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.setShowToolTips
        :args:
            bool
        :description: QtChart/QLegend-setShowToolTips-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtChart/QLegend-showEvent-f.rst

    .. sip:method:: PyQt5.QtChart.QLegend.showToolTips
        :returns:
            bool
        :description: QtChart/QLegend-showToolTips-f.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.backgroundVisibleChanged
        :args:
            bool
        :description: QtChart/QLegend-backgroundVisibleChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.borderColorChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-borderColorChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.colorChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-colorChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.fontChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtChart/QLegend-fontChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.labelColorChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QLegend-labelColorChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.markerShapeChanged
        :args:
            :sip:ref:`~PyQt5.QtChart.QLegend.MarkerShape`
        :description: QtChart/QLegend-markerShapeChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.reverseMarkersChanged
        :args:
            bool
        :description: QtChart/QLegend-reverseMarkersChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QLegend.showToolTipsChanged
        :args:
            bool
        :description: QtChart/QLegend-showToolTipsChanged-s.rst
