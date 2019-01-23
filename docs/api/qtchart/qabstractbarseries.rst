:orphan:

.. sip:class:: PyQt5.QtChart.QAbstractBarSeries
    :inherits: :sip:ref:`~PyQt5.QtChart.QAbstractSeries`
    :description: QtChart/QAbstractBarSeries-c.rst

    .. sip:enum:: PyQt5.QtChart.QAbstractBarSeries.LabelsPosition
        :description: QtChart/QAbstractBarSeries-LabelsPosition-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractBarSeries.LabelsPosition.LabelsCenter
            :description: QtChart/QAbstractBarSeries-LabelsPosition-LabelsCenter-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractBarSeries.LabelsPosition.LabelsInsideBase
            :description: QtChart/QAbstractBarSeries-LabelsPosition-LabelsInsideBase-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractBarSeries.LabelsPosition.LabelsInsideEnd
            :description: QtChart/QAbstractBarSeries-LabelsPosition-LabelsInsideEnd-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QAbstractBarSeries.LabelsPosition.LabelsOutsideEnd
            :description: QtChart/QAbstractBarSeries-LabelsPosition-LabelsOutsideEnd-v.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.append
        :args:
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :returns:
            bool
        :description: QtChart/QAbstractBarSeries-append-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.append
        :args:
            Iterable[:sip:ref:`~PyQt5.QtChart.QBarSet`]
        :returns:
            bool
        :description: QtChart/QAbstractBarSeries-append-f-1.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.barSets
        :returns:
            List[:sip:ref:`~PyQt5.QtChart.QBarSet`]
        :description: QtChart/QAbstractBarSeries-barSets-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.barWidth
        :returns:
            float
        :description: QtChart/QAbstractBarSeries-barWidth-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.clear
        :description: QtChart/QAbstractBarSeries-clear-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.count
        :returns:
            int
        :description: QtChart/QAbstractBarSeries-count-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.insert
        :args:
            int
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :returns:
            bool
        :description: QtChart/QAbstractBarSeries-insert-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.isLabelsVisible
        :returns:
            bool
        :description: QtChart/QAbstractBarSeries-isLabelsVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.labelsAngle
        :returns:
            float
        :description: QtChart/QAbstractBarSeries-labelsAngle-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.labelsFormat
        :returns:
            str
        :description: QtChart/QAbstractBarSeries-labelsFormat-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.labelsPosition
        :returns:
            :sip:ref:`~PyQt5.QtChart.QAbstractBarSeries.LabelsPosition`
        :description: QtChart/QAbstractBarSeries-labelsPosition-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.labelsPrecision
        :returns:
            int
        :description: QtChart/QAbstractBarSeries-labelsPrecision-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.__len__
        :returns:
            int
        :description: QtChart/QAbstractBarSeries-__len__-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.remove
        :args:
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :returns:
            bool
        :description: QtChart/QAbstractBarSeries-remove-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.setBarWidth
        :args:
            float
        :description: QtChart/QAbstractBarSeries-setBarWidth-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.setLabelsAngle
        :args:
            float
        :description: QtChart/QAbstractBarSeries-setLabelsAngle-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.setLabelsFormat
        :args:
            str
        :description: QtChart/QAbstractBarSeries-setLabelsFormat-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.setLabelsPosition
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractBarSeries.LabelsPosition`
        :description: QtChart/QAbstractBarSeries-setLabelsPosition-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.setLabelsPrecision
        :args:
            int
        :description: QtChart/QAbstractBarSeries-setLabelsPrecision-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.setLabelsVisible
        :args:
            visible: bool = True
        :description: QtChart/QAbstractBarSeries-setLabelsVisible-f.rst

    .. sip:method:: PyQt5.QtChart.QAbstractBarSeries.take
        :args:
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :returns:
            bool
        :description: QtChart/QAbstractBarSeries-take-f.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.barsetsAdded
        :args:
            Iterable[:sip:ref:`~PyQt5.QtChart.QBarSet`]
        :description: QtChart/QAbstractBarSeries-barsetsAdded-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.barsetsRemoved
        :args:
            Iterable[:sip:ref:`~PyQt5.QtChart.QBarSet`]
        :description: QtChart/QAbstractBarSeries-barsetsRemoved-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.clicked
        :args:
            int
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :description: QtChart/QAbstractBarSeries-clicked-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.countChanged
        :description: QtChart/QAbstractBarSeries-countChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.doubleClicked
        :args:
            int
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :description: QtChart/QAbstractBarSeries-doubleClicked-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.hovered
        :args:
            bool
            int
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :description: QtChart/QAbstractBarSeries-hovered-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.labelsAngleChanged
        :args:
            float
        :description: QtChart/QAbstractBarSeries-labelsAngleChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.labelsFormatChanged
        :args:
            str
        :description: QtChart/QAbstractBarSeries-labelsFormatChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.labelsPositionChanged
        :args:
            :sip:ref:`~PyQt5.QtChart.QAbstractBarSeries.LabelsPosition`
        :description: QtChart/QAbstractBarSeries-labelsPositionChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.labelsPrecisionChanged
        :args:
            int
        :description: QtChart/QAbstractBarSeries-labelsPrecisionChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.labelsVisibleChanged
        :description: QtChart/QAbstractBarSeries-labelsVisibleChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.pressed
        :args:
            int
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :description: QtChart/QAbstractBarSeries-pressed-s.rst

    .. sip:signal:: PyQt5.QtChart.QAbstractBarSeries.released
        :args:
            int
            :sip:ref:`~PyQt5.QtChart.QBarSet`
        :description: QtChart/QAbstractBarSeries-released-s.rst
