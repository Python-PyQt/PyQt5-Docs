.. sip:method-description::
    :status: todo
    :pysig: 1f0b1213f09df274532ffd52afcda563
    :realsig: () const
    :digest: 4f7f59a8504fc6fd755516bd33a26fa6

Returns the background mode in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBackgroundMode` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
