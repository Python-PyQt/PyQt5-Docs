.. sip:class-description::
    :status: todo
    :brief: Final state
    :digest: fcdff49b21023d675f0b500042c715b8

The :sip:ref:`~PyQt5.QtCore.QFinalState` class provides a final state.

A final state is used to communicate that (part of) a :sip:ref:`~PyQt5.QtCore.QStateMachine` has finished its work. When a final top-level state is entered, the state machine's finished() signal is emitted. In general, when a final substate (a child of a :sip:ref:`~PyQt5.QtCore.QState`) is entered, the parent state's :sip:ref:`~PyQt5.QtCore.QState.finished`\ () signal is emitted. :sip:ref:`~PyQt5.QtCore.QFinalState` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

To use a final state, you create a :sip:ref:`~PyQt5.QtCore.QFinalState` object and add a transition to it from another state. Example:

::

    QPushButton button;

    QStateMachine machine;
    QState *s1 = new QState();
    QFinalState *s2 = new QFinalState();
    s1->addTransition(&button, SIGNAL(clicked()), s2);
    machine.addState(s1);
    machine.addState(s2);

    QObject::connect(&machine, SIGNAL(finished()), QApplication::instance(), SLOT(quit()));
    machine.setInitialState(s1);
    machine.start();

.. seealso:: :sip:ref:`~PyQt5.QtCore.QState.finished`.
