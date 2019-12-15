:orphan:

.. sip:class:: PyQt5.QtChart.QChart
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QGraphicsWidget`
    :description: QtChart/QChart-c.rst

    .. sip:enum:: PyQt5.QtChart.QChart.AnimationOption
        :description: QtChart/QChart-AnimationOption-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.AnimationOption.AllAnimations
            :description: QtChart/QChart-AnimationOption-AllAnimations-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.AnimationOption.GridAxisAnimations
            :description: QtChart/QChart-AnimationOption-GridAxisAnimations-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.AnimationOption.NoAnimation
            :description: QtChart/QChart-AnimationOption-NoAnimation-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.AnimationOption.SeriesAnimations
            :description: QtChart/QChart-AnimationOption-SeriesAnimations-v.rst

    .. sip:enum:: PyQt5.QtChart.QChart.ChartTheme
        :description: QtChart/QChart-ChartTheme-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeBlueCerulean
            :description: QtChart/QChart-ChartTheme-ChartThemeBlueCerulean-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeBlueIcy
            :description: QtChart/QChart-ChartTheme-ChartThemeBlueIcy-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeBlueNcs
            :description: QtChart/QChart-ChartTheme-ChartThemeBlueNcs-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeBrownSand
            :description: QtChart/QChart-ChartTheme-ChartThemeBrownSand-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeDark
            :description: QtChart/QChart-ChartTheme-ChartThemeDark-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeHighContrast
            :description: QtChart/QChart-ChartTheme-ChartThemeHighContrast-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeLight
            :description: QtChart/QChart-ChartTheme-ChartThemeLight-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartTheme.ChartThemeQt
            :description: QtChart/QChart-ChartTheme-ChartThemeQt-v.rst

    .. sip:enum:: PyQt5.QtChart.QChart.ChartType
        :description: QtChart/QChart-ChartType-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartType.ChartTypeCartesian
            :description: QtChart/QChart-ChartType-ChartTypeCartesian-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartType.ChartTypePolar
            :description: QtChart/QChart-ChartType-ChartTypePolar-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QChart.ChartType.ChartTypeUndefined
            :description: QtChart/QChart-ChartType-ChartTypeUndefined-v.rst

    .. sip:method:: PyQt5.QtChart.QChart.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtChart/QChart-__init__-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.addAxis
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :description: QtChart/QChart-addAxis-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.addSeries
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractSeries`
        :description: QtChart/QChart-addSeries-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.animationDuration
        :returns:
            int
        :description: QtChart/QChart-animationDuration-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.animationEasingCurve
        :returns:
            :sip:ref:`~PyQt5.QtCore.QEasingCurve`
        :description: QtChart/QChart-animationEasingCurve-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.animationOptions
        :returns:
            :sip:ref:`~PyQt5.QtChart.QChart.AnimationOptions`
        :description: QtChart/QChart-animationOptions-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.axes
        :args:
            orientation: Union[:sip:ref:`~PyQt5.QtCore.Qt.Orientations`, :sip:ref:`~PyQt5.QtCore.Qt.Orientation`] = Qt.Orientation.Horizontal|Qt.Orientation.Vertical
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :returns:
            List[:sip:ref:`~PyQt5.QtChart.QAbstractAxis`]
        :description: QtChart/QChart-axes-f-1.rst

    .. sip:method:: PyQt5.QtChart.QChart.axisX
        :args:
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :returns:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
        :description: QtChart/QChart-axisX-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.axisY
        :args:
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :returns:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
        :description: QtChart/QChart-axisY-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.backgroundBrush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtChart/QChart-backgroundBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.backgroundPen
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPen`
        :description: QtChart/QChart-backgroundPen-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.backgroundRoundness
        :returns:
            float
        :description: QtChart/QChart-backgroundRoundness-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.chartType
        :returns:
            :sip:ref:`~PyQt5.QtChart.QChart.ChartType`
        :description: QtChart/QChart-chartType-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.createDefaultAxes
        :description: QtChart/QChart-createDefaultAxes-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.isBackgroundVisible
        :returns:
            bool
        :description: QtChart/QChart-isBackgroundVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.isDropShadowEnabled
        :returns:
            bool
        :description: QtChart/QChart-isDropShadowEnabled-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.isPlotAreaBackgroundVisible
        :returns:
            bool
        :description: QtChart/QChart-isPlotAreaBackgroundVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.isZoomed
        :returns:
            bool
        :description: QtChart/QChart-isZoomed-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.legend
        :returns:
            :sip:ref:`~PyQt5.QtChart.QLegend`
        :description: QtChart/QChart-legend-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.locale
        :returns:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtChart/QChart-locale-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.localizeNumbers
        :returns:
            bool
        :description: QtChart/QChart-localizeNumbers-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.mapToPosition
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtChart/QChart-mapToPosition-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.mapToValue
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtChart/QChart-mapToValue-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.margins
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMargins`
        :description: QtChart/QChart-margins-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.plotArea
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtChart/QChart-plotArea-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.plotAreaBackgroundBrush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtChart/QChart-plotAreaBackgroundBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.plotAreaBackgroundPen
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPen`
        :description: QtChart/QChart-plotAreaBackgroundPen-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.removeAllSeries
        :description: QtChart/QChart-removeAllSeries-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.removeAxis
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
        :description: QtChart/QChart-removeAxis-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.removeSeries
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractSeries`
        :description: QtChart/QChart-removeSeries-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.scroll
        :args:
            float
            float
        :description: QtChart/QChart-scroll-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.series
        :returns:
            List[:sip:ref:`~PyQt5.QtChart.QAbstractSeries`]
        :description: QtChart/QChart-series-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setAnimationDuration
        :args:
            int
        :description: QtChart/QChart-setAnimationDuration-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setAnimationEasingCurve
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QEasingCurve`, :sip:ref:`~PyQt5.QtCore.QEasingCurve.Type`]
        :description: QtChart/QChart-setAnimationEasingCurve-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setAnimationOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtChart.QChart.AnimationOptions`, :sip:ref:`~PyQt5.QtChart.QChart.AnimationOption`]
        :description: QtChart/QChart-setAnimationOptions-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setAxisX
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :description: QtChart/QChart-setAxisX-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setAxisY
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :description: QtChart/QChart-setAxisY-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setBackgroundBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QChart-setBackgroundBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setBackgroundPen
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QPen`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QChart-setBackgroundPen-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setBackgroundRoundness
        :args:
            float
        :description: QtChart/QChart-setBackgroundRoundness-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setBackgroundVisible
        :args:
            visible: bool = True
        :description: QtChart/QChart-setBackgroundVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setDropShadowEnabled
        :args:
            enabled: bool = True
        :description: QtChart/QChart-setDropShadowEnabled-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtChart/QChart-setLocale-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setLocalizeNumbers
        :args:
            bool
        :description: QtChart/QChart-setLocalizeNumbers-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setMargins
        :args:
            :sip:ref:`~PyQt5.QtCore.QMargins`
        :description: QtChart/QChart-setMargins-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setPlotArea
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtChart/QChart-setPlotArea-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setPlotAreaBackgroundBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QChart-setPlotAreaBackgroundBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setPlotAreaBackgroundPen
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QPen`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QChart-setPlotAreaBackgroundPen-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setPlotAreaBackgroundVisible
        :args:
            visible: bool = True
        :description: QtChart/QChart-setPlotAreaBackgroundVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setTheme
        :args:
            :sip:ref:`~PyQt5.QtChart.QChart.ChartTheme`
        :description: QtChart/QChart-setTheme-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setTitle
        :args:
            str
        :description: QtChart/QChart-setTitle-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setTitleBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QChart-setTitleBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.setTitleFont
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtChart/QChart-setTitleFont-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.theme
        :returns:
            :sip:ref:`~PyQt5.QtChart.QChart.ChartTheme`
        :description: QtChart/QChart-theme-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.title
        :returns:
            str
        :description: QtChart/QChart-title-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.titleBrush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtChart/QChart-titleBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.titleFont
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtChart/QChart-titleFont-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.zoom
        :args:
            float
        :description: QtChart/QChart-zoom-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.zoomIn
        :description: QtChart/QChart-zoomIn-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.zoomIn
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtChart/QChart-zoomIn-f-1.rst

    .. sip:method:: PyQt5.QtChart.QChart.zoomOut
        :description: QtChart/QChart-zoomOut-f.rst

    .. sip:method:: PyQt5.QtChart.QChart.zoomReset
        :description: QtChart/QChart-zoomReset-f.rst

    .. sip:signal:: PyQt5.QtChart.QChart.plotAreaChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtChart/QChart-plotAreaChanged-s.rst
