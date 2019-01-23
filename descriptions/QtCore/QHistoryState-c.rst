.. sip:class-description::
    :status: todo
    :brief: Means of returning to a previously active substate
    :digest: 95fa98dd8eb6f147b57b6505b486c346

The :sip:ref:`~PyQt5.QtCore.QHistoryState` class provides a means of returning to a previously active substate.

A history state is a pseudo-state that represents the child state that the parent state was in the last time the parent state was exited. A transition with a history state as its target is in fact a transition to one or more other child states of the parent state. :sip:ref:`~PyQt5.QtCore.QHistoryState` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

Use the :sip:ref:`~PyQt5.QtCore.QHistoryState.setDefaultState` function to set the state that should be entered if the parent state has never been entered. Example:

::

    QStateMachine machine;

    QState *s1 = new QState();
    QState *s11 = new QState(s1);
    QState *s12 = new QState(s1);

    QHistoryState *s1h = new QHistoryState(s1);
    s1h->setDefaultState(s11);

    machine.addState(s1);

    QState *s2 = new QState();
    machine.addState(s2);

    QPushButton *button = new QPushButton();
    // Clicking the button will cause the state machine to enter the child state
    // that s1 was in the last time s1 was exited, or the history state's default
    // state if s1 has never been entered.
    s1->addTransition(button, SIGNAL(clicked()), s1h);

If more than one default state has to be entered, or if the transition to the default state(s) has to be acted upon, the :sip:ref:`~PyQt5.QtCore.QHistoryState.defaultTransition` should be set instead. Note that the eventTest() method of that transition will never be called: the selection and execution of the transition is done automatically when entering the history state.

By default a history state is shallow, meaning that it won't remember nested states. This can be configured through the :sip:ref:`~PyQt5.QtCore.QHistoryState.historyType` property.
