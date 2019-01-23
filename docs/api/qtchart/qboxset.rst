:orphan:

.. sip:class:: PyQt5.QtChart.QBoxSet
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtChart/QBoxSet-c.rst

    .. sip:enum:: PyQt5.QtChart.QBoxSet.ValuePositions
        :description: QtChart/QBoxSet-ValuePositions-e.rst

        .. sip:enum-member:: PyQt5.QtChart.QBoxSet.ValuePositions.LowerExtreme
            :description: QtChart/QBoxSet-ValuePositions-LowerExtreme-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QBoxSet.ValuePositions.LowerQuartile
            :description: QtChart/QBoxSet-ValuePositions-LowerQuartile-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QBoxSet.ValuePositions.Median
            :description: QtChart/QBoxSet-ValuePositions-Median-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QBoxSet.ValuePositions.UpperExtreme
            :description: QtChart/QBoxSet-ValuePositions-UpperExtreme-v.rst

        .. sip:enum-member:: PyQt5.QtChart.QBoxSet.ValuePositions.UpperQuartile
            :description: QtChart/QBoxSet-ValuePositions-UpperQuartile-v.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.__init__
        :args:
            label: str = ''
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtChart/QBoxSet-__init__-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.__init__
        :args:
            float
            float
            float
            float
            float
            label: str = ''
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtChart/QBoxSet-__init__-f-1.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.append
        :args:
            float
        :description: QtChart/QBoxSet-append-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.append
        :args:
            Iterable[float]
        :description: QtChart/QBoxSet-append-f-1.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.at
        :args:
            int
        :returns:
            float
        :description: QtChart/QBoxSet-at-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.brush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtChart/QBoxSet-brush-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.clear
        :description: QtChart/QBoxSet-clear-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.count
        :returns:
            int
        :description: QtChart/QBoxSet-count-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.__getitem__
        :args:
            int
        :returns:
            float
        :description: QtChart/QBoxSet-__getitem__-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.label
        :returns:
            str
        :description: QtChart/QBoxSet-label-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.__len__
        :returns:
            int
        :description: QtChart/QBoxSet-__len__-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.__lshift__
        :args:
            float
        :returns:
            :sip:ref:`~PyQt5.QtChart.QBoxSet`
        :description: QtChart/QBoxSet-__lshift__-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.pen
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPen`
        :description: QtChart/QBoxSet-pen-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.setBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QBoxSet-setBrush-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.setLabel
        :args:
            str
        :description: QtChart/QBoxSet-setLabel-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.setPen
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QPen`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtChart/QBoxSet-setPen-f.rst

    .. sip:method:: PyQt5.QtChart.QBoxSet.setValue
        :args:
            int
            float
        :description: QtChart/QBoxSet-setValue-f.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.brushChanged
        :description: QtChart/QBoxSet-brushChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.cleared
        :description: QtChart/QBoxSet-cleared-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.clicked
        :description: QtChart/QBoxSet-clicked-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.doubleClicked
        :description: QtChart/QBoxSet-doubleClicked-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.hovered
        :args:
            bool
        :description: QtChart/QBoxSet-hovered-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.penChanged
        :description: QtChart/QBoxSet-penChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.pressed
        :description: QtChart/QBoxSet-pressed-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.released
        :description: QtChart/QBoxSet-released-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.valueChanged
        :args:
            int
        :description: QtChart/QBoxSet-valueChanged-s.rst

    .. sip:signal:: PyQt5.QtChart.QBoxSet.valuesChanged
        :description: QtChart/QBoxSet-valuesChanged-s.rst
