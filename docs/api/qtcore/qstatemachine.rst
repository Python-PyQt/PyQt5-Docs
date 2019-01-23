:orphan:

.. sip:class:: PyQt5.QtCore.QStateMachine
    :inherits: :sip:ref:`~PyQt5.QtCore.QState`
    :description: QtCore/QStateMachine-c.rst

    .. sip:enum:: PyQt5.QtCore.QStateMachine.Error
        :description: QtCore/QStateMachine-Error-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QStateMachine.Error.NoCommonAncestorForTransitionError
            :description: QtCore/QStateMachine-Error-NoCommonAncestorForTransitionError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QStateMachine.Error.NoDefaultStateInHistoryStateError
            :description: QtCore/QStateMachine-Error-NoDefaultStateInHistoryStateError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QStateMachine.Error.NoError
            :description: QtCore/QStateMachine-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QStateMachine.Error.NoInitialStateError
            :description: QtCore/QStateMachine-Error-NoInitialStateError-v.rst

    .. sip:enum:: PyQt5.QtCore.QStateMachine.EventPriority
        :description: QtCore/QStateMachine-EventPriority-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QStateMachine.EventPriority.HighPriority
            :description: QtCore/QStateMachine-EventPriority-HighPriority-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QStateMachine.EventPriority.NormalPriority
            :description: QtCore/QStateMachine-EventPriority-NormalPriority-v.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QStateMachine-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QState.ChildMode`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QStateMachine-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.addDefaultAnimation
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractAnimation`
        :description: QtCore/QStateMachine-addDefaultAnimation-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.addState
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QStateMachine-addState-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.cancelDelayedEvent
        :args:
            int
        :returns:
            bool
        :description: QtCore/QStateMachine-cancelDelayedEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.clearError
        :description: QtCore/QStateMachine-clearError-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.configuration
        :returns:
            Set[:sip:ref:`~PyQt5.QtCore.QAbstractState`]
        :description: QtCore/QStateMachine-configuration-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.defaultAnimations
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QAbstractAnimation`]
        :description: QtCore/QStateMachine-defaultAnimations-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.error
        :returns:
            :sip:ref:`~PyQt5.QtCore.QStateMachine.Error`
        :description: QtCore/QStateMachine-error-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.errorString
        :returns:
            str
        :description: QtCore/QStateMachine-errorString-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QStateMachine-event-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QStateMachine-eventFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.globalRestorePolicy
        :returns:
            :sip:ref:`~PyQt5.QtCore.QState.RestorePolicy`
        :description: QtCore/QStateMachine-globalRestorePolicy-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.isAnimated
        :returns:
            bool
        :description: QtCore/QStateMachine-isAnimated-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.isRunning
        :returns:
            bool
        :description: QtCore/QStateMachine-isRunning-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.onEntry
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QStateMachine-onEntry-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.onExit
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QStateMachine-onExit-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.postDelayedEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
            int
        :returns:
            int
        :description: QtCore/QStateMachine-postDelayedEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.postEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
            priority: :sip:ref:`~PyQt5.QtCore.QStateMachine.EventPriority` = :sip:ref:`~PyQt5.QtCore.QStateMachine.EventPriority.NormalPriority`
        :description: QtCore/QStateMachine-postEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.removeDefaultAnimation
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractAnimation`
        :description: QtCore/QStateMachine-removeDefaultAnimation-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.removeState
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QStateMachine-removeState-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.setAnimated
        :args:
            bool
        :description: QtCore/QStateMachine-setAnimated-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.setGlobalRestorePolicy
        :args:
            :sip:ref:`~PyQt5.QtCore.QState.RestorePolicy`
        :description: QtCore/QStateMachine-setGlobalRestorePolicy-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.setRunning
        :args:
            bool
        :description: QtCore/QStateMachine-setRunning-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.start
        :description: QtCore/QStateMachine-start-f.rst

    .. sip:method:: PyQt5.QtCore.QStateMachine.stop
        :description: QtCore/QStateMachine-stop-f.rst

    .. sip:signal:: PyQt5.QtCore.QStateMachine.runningChanged
        :args:
            bool
        :description: QtCore/QStateMachine-runningChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QStateMachine.started
        :description: QtCore/QStateMachine-started-s.rst

    .. sip:signal:: PyQt5.QtCore.QStateMachine.stopped
        :description: QtCore/QStateMachine-stopped-s.rst
