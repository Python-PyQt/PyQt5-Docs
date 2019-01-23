:orphan:

.. sip:class:: PyQt5.QtCore.QState
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractState`
    :description: QtCore/QState-c.rst

    .. sip:enum:: PyQt5.QtCore.QState.ChildMode
        :description: QtCore/QState-ChildMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QState.ChildMode.ExclusiveStates
            :description: QtCore/QState-ChildMode-ExclusiveStates-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QState.ChildMode.ParallelStates
            :description: QtCore/QState-ChildMode-ParallelStates-v.rst

    .. sip:enum:: PyQt5.QtCore.QState.RestorePolicy
        :description: QtCore/QState-RestorePolicy-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QState.RestorePolicy.DontRestoreProperties
            :description: QtCore/QState-RestorePolicy-DontRestoreProperties-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QState.RestorePolicy.RestoreProperties
            :description: QtCore/QState-RestorePolicy-RestoreProperties-v.rst

    .. sip:method:: PyQt5.QtCore.QState.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QState` = None
        :description: QtCore/QState-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QState.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QState.ChildMode`
            parent: :sip:ref:`~PyQt5.QtCore.QState` = None
        :description: QtCore/QState-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QState.addTransition
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractTransition`
        :description: QtCore/QState-addTransition-f.rst

    .. sip:method:: PyQt5.QtCore.QState.addTransition
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractTransition`
        :description: QtCore/QState-addTransition-f-1.rst

    .. sip:method:: PyQt5.QtCore.QState.addTransition
        :args:
            pyqtBoundSignal
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSignalTransition`
        :description: QtCore/QState-addTransition-f-2.rst

    .. sip:method:: PyQt5.QtCore.QState.assignProperty
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            str
            Any
        :description: QtCore/QState-assignProperty-f.rst

    .. sip:method:: PyQt5.QtCore.QState.childMode
        :returns:
            :sip:ref:`~PyQt5.QtCore.QState.ChildMode`
        :description: QtCore/QState-childMode-f.rst

    .. sip:method:: PyQt5.QtCore.QState.errorState
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QState-errorState-f.rst

    .. sip:method:: PyQt5.QtCore.QState.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QState-event-f.rst

    .. sip:method:: PyQt5.QtCore.QState.initialState
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QState-initialState-f.rst

    .. sip:method:: PyQt5.QtCore.QState.onEntry
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QState-onEntry-f.rst

    .. sip:method:: PyQt5.QtCore.QState.onExit
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QState-onExit-f.rst

    .. sip:method:: PyQt5.QtCore.QState.removeTransition
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractTransition`
        :description: QtCore/QState-removeTransition-f.rst

    .. sip:method:: PyQt5.QtCore.QState.setChildMode
        :args:
            :sip:ref:`~PyQt5.QtCore.QState.ChildMode`
        :description: QtCore/QState-setChildMode-f.rst

    .. sip:method:: PyQt5.QtCore.QState.setErrorState
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QState-setErrorState-f.rst

    .. sip:method:: PyQt5.QtCore.QState.setInitialState
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QState-setInitialState-f.rst

    .. sip:method:: PyQt5.QtCore.QState.transitions
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QAbstractTransition`]
        :description: QtCore/QState-transitions-f.rst

    .. sip:signal:: PyQt5.QtCore.QState.childModeChanged
        :description: QtCore/QState-childModeChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QState.errorStateChanged
        :description: QtCore/QState-errorStateChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QState.finished
        :description: QtCore/QState-finished-s.rst

    .. sip:signal:: PyQt5.QtCore.QState.initialStateChanged
        :description: QtCore/QState-initialStateChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QState.propertiesAssigned
        :description: QtCore/QState-propertiesAssigned-s.rst
