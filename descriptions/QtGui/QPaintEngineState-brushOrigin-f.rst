.. sip:method-description::
    :status: todo
    :pysig: 3c262cc6fe718e83c8acc57a39925789
    :realsig: () const
    :digest: eae999d70cd2c87c20206ab8f8b9e572

Returns the brush origin in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBrushOrigin` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
