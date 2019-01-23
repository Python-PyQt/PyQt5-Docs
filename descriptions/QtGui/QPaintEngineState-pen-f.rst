.. sip:method-description::
    :status: todo
    :pysig: 9bcf688abed01c35c8ac5557cde079b2
    :realsig: () const
    :digest: 1f66a4428b63c0cd4e69ae34828b4551

Returns the pen in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyPen` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
