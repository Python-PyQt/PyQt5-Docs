:orphan:

.. sip:class:: PyQt5.QtChart.QCategoryAxis
    :inherits: :sip:ref:`~PyQt5.QtChart.QValueAxis`
    :description: QtChart/QCategoryAxis-c.rst

    .. sip:enum:: PyQt5.QtChart.QCategoryAxis.AxisLabelsPosition
        :description: QtChart/QCategoryAxis-AxisLabelsPosition-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QCategoryAxis.AxisLabelsPosition.AxisLabelsPositionCenter
            :description: QtChart/QCategoryAxis-AxisLabelsPosition-AxisLabelsPositionCenter-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QCategoryAxis.AxisLabelsPosition.AxisLabelsPositionOnValue
            :description: QtChart/QCategoryAxis-AxisLabelsPosition-AxisLabelsPositionOnValue-v.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtChart/QCategoryAxis-__init__-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.append
        :args:
            str
            float
        :description: QtChart/QCategoryAxis-append-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.categoriesLabels
        :returns:
            List[str]
        :description: QtChart/QCategoryAxis-categoriesLabels-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.count
        :returns:
            int
        :description: QtChart/QCategoryAxis-count-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.endValue
        :args:
            str
        :returns:
            float
        :description: QtChart/QCategoryAxis-endValue-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.labelsPosition
        :returns:
            :sip:ref:`~PyQt5.QtChart.QCategoryAxis.AxisLabelsPosition`
        :description: QtChart/QCategoryAxis-labelsPosition-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.__len__
        :returns:
            int
        :description: QtChart/QCategoryAxis-__len__-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.remove
        :args:
            str
        :description: QtChart/QCategoryAxis-remove-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.replaceLabel
        :args:
            str
            str
        :description: QtChart/QCategoryAxis-replaceLabel-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.setLabelsPosition
        :args:
            :sip:ref:`~PyQt5.QtChart.QCategoryAxis.AxisLabelsPosition`
        :description: QtChart/QCategoryAxis-setLabelsPosition-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.setStartValue
        :args:
            float
        :description: QtChart/QCategoryAxis-setStartValue-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.startValue
        :args:
            categoryLabel: str = ''
        :returns:
            float
        :description: QtChart/QCategoryAxis-startValue-f.rst

    .. sip:method:: PyQt5.QtChart.QCategoryAxis.type
        :returns:
            :sip:ref:`~PyQt5.QtChart.QAbstractAxis.AxisType`
        :description: QtChart/QCategoryAxis-type-f.rst

    .. sip:signal:: PyQt5.QtChart.QCategoryAxis.categoriesChanged
        :description: QtChart/QCategoryAxis-categoriesChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QCategoryAxis.labelsPositionChanged
        :args:
            :sip:ref:`~PyQt5.QtChart.QCategoryAxis.AxisLabelsPosition`
        :description: QtChart/QCategoryAxis-labelsPositionChanged-s.rst
