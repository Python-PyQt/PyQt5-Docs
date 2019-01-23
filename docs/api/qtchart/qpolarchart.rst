:orphan:

.. sip:class:: PyQt5.QtChart.QPolarChart
    :inherits: :sip:ref:`~PyQt5.QtChart.QChart`
    :description: QtChart/QPolarChart-c.rst

    .. sip:enum:: PyQt5.QtChart.QPolarChart.PolarOrientation
        :description: QtChart/QPolarChart-PolarOrientation-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QPolarChart.PolarOrientation.PolarOrientationAngular
            :description: QtChart/QPolarChart-PolarOrientation-PolarOrientationAngular-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QPolarChart.PolarOrientation.PolarOrientationRadial
            :description: QtChart/QPolarChart-PolarOrientation-PolarOrientationRadial-v.rst

    .. sip:method:: PyQt5.QtChart.QPolarChart.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtChart/QPolarChart-__init__-f.rst

    .. sip:method:: PyQt5.QtChart.QPolarChart.addAxis
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
            :sip:ref:`~PyQt5.QtChart.QPolarChart.PolarOrientation`
        :description: QtChart/QPolarChart-addAxis-f.rst

    .. sip:method:: PyQt5.QtChart.QPolarChart.axes
        :args:
            polarOrientation: :sip:ref:`~PyQt5.QtChart.QPolarChart.PolarOrientations` = QFlags<QtCharts.QPolarChart.PolarOrientation>(QFlag(3))
            series: :sip:ref:`~PyQt5.QtChart.QAbstractSeries` = None
        :returns:
            List[:sip:ref:`~PyQt5.QtChart.QAbstractAxis`]
        :description: QtChart/QPolarChart-axes-f.rst

    .. sip:method:: PyQt5.QtChart.QPolarChart.axisPolarOrientation
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis`
        :returns:
            :sip:ref:`~PyQt5.QtChart.QPolarChart.PolarOrientation`
        :static:
        :description: QtChart/QPolarChart-axisPolarOrientation-f.rst
