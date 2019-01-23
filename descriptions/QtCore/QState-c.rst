.. sip:class-description::
    :status: todo
    :brief: General-purpose state for QStateMachine
    :digest: ae8bb43cecaceab65e5abac0f0b278fd

The :sip:ref:`~PyQt5.QtCore.QState` class provides a general-purpose state for :sip:ref:`~PyQt5.QtCore.QStateMachine`.

:sip:ref:`~PyQt5.QtCore.QState` objects can have child states, and can have transitions to other states. :sip:ref:`~PyQt5.QtCore.QState` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

The :sip:ref:`~PyQt5.QtCore.QState.addTransition` function adds a transition. The :sip:ref:`~PyQt5.QtCore.QState.removeTransition` function removes a transition. The :sip:ref:`~PyQt5.QtCore.QState.transitions` function returns the state's outgoing transitions.

The :sip:ref:`~PyQt5.QtCore.QState.assignProperty` function is used for defining property assignments that should be performed when a state is entered.

Top-level states must be passed a :sip:ref:`~PyQt5.QtCore.QStateMachine` object as their parent state, or added to a state machine using :sip:ref:`~PyQt5.QtCore.QStateMachine.addState`.

.. _qstate-states-with-child-states:

States with Child States
------------------------

The :sip:ref:`~PyQt5.QtCore.QState.childMode` property determines how child states are treated. For non-parallel state groups, the :sip:ref:`~PyQt5.QtCore.QState.setInitialState` function must be called to set the initial state. The child states are mutually exclusive states, and the state machine needs to know which child state to enter when the parent state is the target of a transition.

The state emits the :sip:ref:`~PyQt5.QtCore.QState.finished` signal when a final child state (\ :sip:ref:`~PyQt5.QtCore.QFinalState`) is entered.

The :sip:ref:`~PyQt5.QtCore.QState.setErrorState` sets the state's error state. The error state is the state that the state machine will transition to if an error is detected when attempting to enter the state (e.g. because no initial state has been set).
