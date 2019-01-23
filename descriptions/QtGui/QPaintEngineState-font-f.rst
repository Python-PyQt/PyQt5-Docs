.. sip:method-description::
    :status: todo
    :pysig: 62f63e09cf8b2bc15c56d1b562ef9090
    :realsig: () const
    :digest: 36bcab9e716c657373abb5283d8baf3f

Returns the font in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyFont` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
