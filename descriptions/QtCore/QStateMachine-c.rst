.. sip:class-description::
    :status: todo
    :brief: Hierarchical finite state machine
    :digest: a178557feb9c4e269e1553bd34094bc9

The :sip:ref:`~PyQt5.QtCore.QStateMachine` class provides a hierarchical finite state machine.

:sip:ref:`~PyQt5.QtCore.QStateMachine` is based on the concepts and notation of Statecharts. :sip:ref:`~PyQt5.QtCore.QStateMachine` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

A state machine manages a set of states (classes that inherit from :sip:ref:`~PyQt5.QtCore.QAbstractState`) and transitions (descendants of :sip:ref:`~PyQt5.QtCore.QAbstractTransition`) between those states; these states and transitions define a state graph. Once a state graph has been built, the state machine can execute it. :sip:ref:`~PyQt5.QtCore.QStateMachine`'s execution algorithm is based on the State Chart XML (SCXML) algorithm. The framework's `overview <https://doc.qt.io/qt-5/statemachine-api.html>`_ gives several state graphs and the code to build them.

Use the :sip:ref:`~PyQt5.QtCore.QStateMachine.addState` function to add a top-level state to the state machine. States are removed with the :sip:ref:`~PyQt5.QtCore.QStateMachine.removeState` function. Removing states while the machine is running is discouraged.

Before the machine can be started, the initial state must be set. The initial state is the state that the machine enters when started. You can then :sip:ref:`~PyQt5.QtCore.QStateMachine.start` the state machine. The :sip:ref:`~PyQt5.QtCore.QStateMachine.started` signal is emitted when the initial state is entered.

The machine is event driven and keeps its own event loop. Events are posted to the machine through :sip:ref:`~PyQt5.QtCore.QStateMachine.postEvent`. Note that this means that it executes asynchronously, and that it will not progress without a running event loop. You will normally not have to post events to the machine directly as Qt's transitions, e.g., :sip:ref:`~PyQt5.QtCore.QEventTransition` and its subclasses, handle this. But for custom transitions triggered by events, :sip:ref:`~PyQt5.QtCore.QStateMachine.postEvent` is useful.

The state machine processes events and takes transitions until a top-level final state is entered; the state machine then emits the finished() signal. You can also :sip:ref:`~PyQt5.QtCore.QStateMachine.stop` the state machine explicitly. The :sip:ref:`~PyQt5.QtCore.QStateMachine.stopped` signal is emitted in this case.

The following snippet shows a state machine that will finish when a button is clicked:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_statemachine_qstatemachine.py
    :lines: 54-66

This code example uses :sip:ref:`~PyQt5.QtCore.QState`, which inherits :sip:ref:`~PyQt5.QtCore.QAbstractState`. The :sip:ref:`~PyQt5.QtCore.QState` class provides a state that you can use to set properties and invoke methods on :sip:ref:`~PyQt5.QtCore.QObject`\ s when the state is entered or exited. It also contains convenience functions for adding transitions, e.g., :sip:ref:`~PyQt5.QtCore.QSignalTransition`\ s as in this example. See the :sip:ref:`~PyQt5.QtCore.QState` class description for further details.

If an error is encountered, the machine will look for an error state, and if one is available, it will enter this state. The types of errors possible are described by the :sip:ref:`~PyQt5.QtCore.QStateMachine.Error` enum. After the error state is entered, the type of the error can be retrieved with :sip:ref:`~PyQt5.QtCore.QStateMachine.error`. The execution of the state graph will not stop when the error state is entered. If no error state applies to the erroneous state, the machine will stop executing and an error message will be printed to the console.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractState`, :sip:ref:`~PyQt5.QtCore.QAbstractTransition`, :sip:ref:`~PyQt5.QtCore.QState`, `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.
