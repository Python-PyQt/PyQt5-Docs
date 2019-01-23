.. sip:method-description::
    :status: todo
    :pysig: c79d17359756e2d0a80da67536bbb7b2
    :realsig: () const
    :digest: 1e6a53bc3195dfb5b7d8e8ac66c15c68

Returns the background brush in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBackground` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
