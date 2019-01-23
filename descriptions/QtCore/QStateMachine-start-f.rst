.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: b76607167148d95e16762d8cc17a6513

Starts this state machine. The machine will reset its configuration and transition to the initial state. When a final top-level state (\ :sip:ref:`~PyQt5.QtCore.QFinalState`) is entered, the machine will emit the finished() signal.

**Note:** A state machine will not run without a running event loop, such as the main application event loop started with :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec` or QApplication::exec().

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStateMachine.started`, finished(), :sip:ref:`~PyQt5.QtCore.QStateMachine.stop`, initialState(), :sip:ref:`~PyQt5.QtCore.QStateMachine.setRunning`.
