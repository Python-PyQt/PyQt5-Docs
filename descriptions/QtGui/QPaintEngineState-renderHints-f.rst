.. sip:method-description::
    :status: todo
    :pysig: 64dd2376f5854213aed7135c910d8700
    :realsig: () const
    :digest: dd56ff9df898dce2343fc0dc34bcfd9f

Returns the render hints in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyHints` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
