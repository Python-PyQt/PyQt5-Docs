:orphan:

.. sip:class:: PyQt5.QtChart.QAbstractSeries
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtChart/QAbstractSeries-c.rst

    .. sip:enum:: PyQt5.QtChart.QAbstractSeries.SeriesType
        :description: QtChart/QAbstractSeries-SeriesType-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeArea
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeArea-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeBar
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeBar-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeBoxPlot
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeBoxPlot-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeCandlestick
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeCandlestick-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeHorizontalBar
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeHorizontalBar-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeHorizontalPercentBar
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeHorizontalPercentBar-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeHorizontalStackedBar
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeHorizontalStackedBar-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeLine
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeLine-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypePercentBar
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypePercentBar-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypePie
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypePie-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeScatter
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeScatter-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeSpline
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeSpline-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractSeries.SeriesType.SeriesTypeStackedBar
            :description: QtChart/QAbstractSeries-SeriesType-SeriesTypeStackedBar-v.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.attachAxis
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
        :returns:
            bool
        :description: QtChart/QAbstractSeries-attachAxis-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.attachedAxes
        :returns:
            List[:sip:ref:`~PyQt5.QtChart.QAbstractAxis`]
        :description: QtChart/QAbstractSeries-attachedAxes-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.chart
        :returns:
            :sip:ref:`~PyQt5.QtChart.QChart`
        :description: QtChart/QAbstractSeries-chart-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.detachAxis
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
        :returns:
            bool
        :description: QtChart/QAbstractSeries-detachAxis-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.hide
        :description: QtChart/QAbstractSeries-hide-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.isVisible
        :returns:
            bool
        :description: QtChart/QAbstractSeries-isVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.name
        :returns:
            str
        :description: QtChart/QAbstractSeries-name-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.opacity
        :returns:
            float
        :description: QtChart/QAbstractSeries-opacity-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.setName
        :args:
            str
        :description: QtChart/QAbstractSeries-setName-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.setOpacity
        :args:
            float
        :description: QtChart/QAbstractSeries-setOpacity-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.setUseOpenGL
        :args:
            enable: bool = True
        :description: QtChart/QAbstractSeries-setUseOpenGL-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.setVisible
        :args:
            visible: bool = True
        :description: QtChart/QAbstractSeries-setVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.show
        :description: QtChart/QAbstractSeries-show-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.type
        :returns:
            :sip:ref:`~PyQt5.QtChart.QAbstractSeries.SeriesType`
        :description: QtChart/QAbstractSeries-type-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractSeries.useOpenGL
        :returns:
            bool
        :description: QtChart/QAbstractSeries-useOpenGL-f.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractSeries.nameChanged
        :description: QtChart/QAbstractSeries-nameChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractSeries.opacityChanged
        :description: QtChart/QAbstractSeries-opacityChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractSeries.useOpenGLChanged
        :description: QtChart/QAbstractSeries-useOpenGLChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractSeries.visibleChanged
        :description: QtChart/QAbstractSeries-visibleChanged-s.rst
