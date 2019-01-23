:orphan:

.. sip:class:: PyQt5.QtCore.QAbstractTransition
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QAbstractTransition-c.rst

    .. sip:enum:: PyQt5.QtCore.QAbstractTransition.TransitionType
        :description: QtCore/QAbstractTransition-TransitionType-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QAbstractTransition.TransitionType.ExternalTransition
            :description: QtCore/QAbstractTransition-TransitionType-ExternalTransition-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QAbstractTransition.TransitionType.InternalTransition
            :description: QtCore/QAbstractTransition-TransitionType-InternalTransition-v.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.__init__
        :args:
            sourceState: :sip:ref:`~PyQt5.QtCore.QState` = None
        :description: QtCore/QAbstractTransition-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.addAnimation
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractAnimation`
        :description: QtCore/QAbstractTransition-addAnimation-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.animations
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QAbstractAnimation`]
        :description: QtCore/QAbstractTransition-animations-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QAbstractTransition-event-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.eventTest
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QAbstractTransition-eventTest-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.machine
        :returns:
            :sip:ref:`~PyQt5.QtCore.QStateMachine`
        :description: QtCore/QAbstractTransition-machine-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.onTransition
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QAbstractTransition-onTransition-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.removeAnimation
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractAnimation`
        :description: QtCore/QAbstractTransition-removeAnimation-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.setTargetState
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QAbstractTransition-setTargetState-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.setTargetStates
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QAbstractState`]
        :description: QtCore/QAbstractTransition-setTargetStates-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.setTransitionType
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractTransition.TransitionType`
        :description: QtCore/QAbstractTransition-setTransitionType-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.sourceState
        :returns:
            :sip:ref:`~PyQt5.QtCore.QState`
        :description: QtCore/QAbstractTransition-sourceState-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.targetState
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractState`
        :description: QtCore/QAbstractTransition-targetState-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.targetStates
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QAbstractState`]
        :description: QtCore/QAbstractTransition-targetStates-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractTransition.transitionType
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractTransition.TransitionType`
        :description: QtCore/QAbstractTransition-transitionType-f.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractTransition.targetStateChanged
        :description: QtCore/QAbstractTransition-targetStateChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractTransition.targetStatesChanged
        :description: QtCore/QAbstractTransition-targetStatesChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractTransition.triggered
        :description: QtCore/QAbstractTransition-triggered-s.rst
