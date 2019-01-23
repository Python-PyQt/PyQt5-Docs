.. sip:class-description::
    :status: todo
    :brief: QObject-specific transition for Qt events
    :digest: 95493b1b73253c3836a4ae5867c6c1ad

The :sip:ref:`~PyQt5.QtCore.QEventTransition` class provides a :sip:ref:`~PyQt5.QtCore.QObject`-specific transition for Qt events.

A :sip:ref:`~PyQt5.QtCore.QEventTransition` object binds an event to a particular :sip:ref:`~PyQt5.QtCore.QObject`. :sip:ref:`~PyQt5.QtCore.QEventTransition` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

Example:

::

    QPushButton *button = ...;
    QState *s1 = ...;
    QState *s2 = ...;
    // If in s1 and the button receives an Enter event, transition to s2
    QEventTransition *enterTransition = new QEventTransition(button, QEvent::Enter);
    enterTransition->setTargetState(s2);
    s1->addTransition(enterTransition);
    // If in s2 and the button receives an Exit event, transition back to s1
    QEventTransition *leaveTransition = new QEventTransition(button, QEvent::Leave);
    leaveTransition->setTargetState(s1);
    s2->addTransition(leaveTransition);

.. _qeventtransition-subclassing:

Subclassing
-----------

When reimplementing the :sip:ref:`~PyQt5.QtCore.QEventTransition.eventTest` function, you should first call the base implementation to verify that the event is a :sip:ref:`~PyQt5.QtCore.QStateMachine.WrappedEvent` for the proper object and event type. You may then cast the event to a :sip:ref:`~PyQt5.QtCore.QStateMachine.WrappedEvent` and get the original event by calling :sip:ref:`~PyQt5.QtCore.QStateMachine.WrappedEvent.event`, and perform additional checks on that object.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QState.addTransition`.
