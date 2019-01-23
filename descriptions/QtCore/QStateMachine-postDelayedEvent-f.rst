.. sip:method-description::
    :status: todo
    :pysig: 3e715e882bde4a3aab92f9a723fce385
    :realsig: (QEvent*,int)
    :digest: cf7b81c9a2e9262b16f2ec011a4743aa

Posts the given *event* for processing by this state machine, with the given *delay* in milliseconds. Returns an identifier associated with the delayed event, or -1 if the event could not be posted.

This function returns immediately. When the delay has expired, the event will be added to the state machine's event queue for processing. The state machine takes ownership of the event and deletes it once it has been processed.

You can only post events when the state machine is running.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStateMachine.cancelDelayedEvent`, :sip:ref:`~PyQt5.QtCore.QStateMachine.postEvent`.
