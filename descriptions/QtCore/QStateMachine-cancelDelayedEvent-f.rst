.. sip:method-description::
    :status: todo
    :pysig: 47bc384ef78158df7bdc68df0f06aef9
    :realsig: (int)
    :digest: b143a05ade6bd2b5cdb0fcd1ab66dc48

Cancels the delayed event identified by the given *id*. The id should be a value returned by a call to :sip:ref:`~PyQt5.QtCore.QStateMachine.postDelayedEvent`. Returns ``true`` if the event was successfully cancelled, otherwise returns ``false``.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStateMachine.postDelayedEvent`.
