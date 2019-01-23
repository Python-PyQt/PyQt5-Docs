.. sip:method-description::
    :status: todo
    :pysig: c79d17359756e2d0a80da67536bbb7b2
    :realsig: () const
    :digest: e6da663620e8a6c6d16c76aa739bb201

Returns the brush in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBrush` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
