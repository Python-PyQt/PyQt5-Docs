.. sip:class-description::
    :status: todo
    :brief: Transition based on a Qt signal
    :digest: 3f374d6a583405621814014e6df8ae44

The :sip:ref:`~PyQt5.QtCore.QSignalTransition` class provides a transition based on a Qt signal.

Typically you would use the overload of :sip:ref:`~PyQt5.QtCore.QState.addTransition` that takes a sender and signal as arguments, rather than creating :sip:ref:`~PyQt5.QtCore.QSignalTransition` objects directly. :sip:ref:`~PyQt5.QtCore.QSignalTransition` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

You can subclass :sip:ref:`~PyQt5.QtCore.QSignalTransition` and reimplement :sip:ref:`~PyQt5.QtCore.QSignalTransition.eventTest` to make a signal transition conditional; the event object passed to :sip:ref:`~PyQt5.QtCore.QSignalTransition.eventTest` will be a :sip:ref:`~PyQt5.QtCore.QStateMachine.SignalEvent` object. Example:

::

    class CheckedTransition : public QSignalTransition
    {
    public:
        CheckedTransition(QCheckBox *check)
            : QSignalTransition(check, SIGNAL(stateChanged(int))) {}
    protected:
        bool eventTest(QEvent *e) {
            if (!QSignalTransition::eventTest(e))
                return false;
            QStateMachine::SignalEvent *se = static_cast<QStateMachine::SignalEvent*>(e);
            return (se->arguments().at(0).toInt() == Qt::Checked);
        }
    };

    ...

    QCheckBox *check = new QCheckBox();
    check->setTristate(true);

    QState *s1 = new QState();
    QState *s2 = new QState();
    CheckedTransition *t1 = new CheckedTransition(check);
    t1->setTargetState(s2);
    s1->addTransition(t1);
