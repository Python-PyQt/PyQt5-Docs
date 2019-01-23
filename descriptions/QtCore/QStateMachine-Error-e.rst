.. sip:enum-description::
    :status: todo
    :digest: bdf602fd7597f4ca687fadbc62718d5c

This enum type defines errors that can occur in the state machine at run time. When the state machine encounters an unrecoverable error at run time, it will set the error code returned by :sip:ref:`~PyQt5.QtCore.QStateMachine.error`, the error message returned by :sip:ref:`~PyQt5.QtCore.QStateMachine.errorString`, and enter an error state based on the context of the error.

.. seealso:: setErrorState().
