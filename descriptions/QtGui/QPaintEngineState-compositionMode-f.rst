.. sip:method-description::
    :status: todo
    :pysig: dc18919ddfa2d4686c7b736f8bfa094b
    :realsig: () const
    :digest: 9ff2fb2c008bd9b754cdaa2564f427f2

Returns the composition mode in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyCompositionMode` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
