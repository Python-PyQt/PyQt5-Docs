.. sip:method-description::
    :status: todo
    :pysig: f8130ffdf2418942b961cffe2251993c
    :realsig: (QEvent*,QStateMachine::EventPriority)
    :digest: f04409ca42ab549a352eb981814293c9

Posts the given *event* of the given *priority* for processing by this state machine.

This function returns immediately. The event is added to the state machine's event queue. Events are processed in the order posted. The state machine takes ownership of the event and deletes it once it has been processed.

You can only post events when the state machine is running or when it is starting up.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStateMachine.postDelayedEvent`.
