:orphan:

.. sip:class:: PyQt5.QtCore.QHistoryState
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractState`
    :description: QtCore/QHistoryState-c.rst

    .. sip:enum:: PyQt5.QtCore.QHistoryState.HistoryType
        :description: QtCore/QHistoryState-HistoryType-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QHistoryState.HistoryType.DeepHistory
            :description: QtCore/QHistoryState-HistoryType-DeepHistory-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QHistoryState.HistoryType.ShallowHistory
            :description: QtCore/QHistoryState-HistoryType-ShallowHistory-v.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QState` = None
        :description: QtCore/QHistoryState-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QHistoryState.HistoryType`
            parent: :sip:ref:`~PyQt5.QtCore.QState` = None
        :description: QtCore/QHistoryState-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.defaultState
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QHistoryState-defaultState-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.defaultTransition
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractTransition`
        :description: QtCore/QHistoryState-defaultTransition-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QHistoryState-event-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.historyType
        :returns:
            :sip:ref:`~PyQt5.QtCore.QHistoryState.HistoryType`
        :description: QtCore/QHistoryState-historyType-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.onEntry
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QHistoryState-onEntry-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.onExit
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QHistoryState-onExit-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.setDefaultState
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QHistoryState-setDefaultState-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.setDefaultTransition
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractTransition`
        :description: QtCore/QHistoryState-setDefaultTransition-f.rst

    .. sip:method:: PyQt5.QtCore.QHistoryState.setHistoryType
        :args:
            :sip:ref:`~PyQt5.QtCore.QHistoryState.HistoryType`
        :description: QtCore/QHistoryState-setHistoryType-f.rst

    .. sip:signal:: PyQt5.QtCore.QHistoryState.defaultStateChanged
        :description: QtCore/QHistoryState-defaultStateChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QHistoryState.defaultTransitionChanged
        :description: QtCore/QHistoryState-defaultTransitionChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QHistoryState.historyTypeChanged
        :description: QtCore/QHistoryState-historyTypeChanged-s.rst
