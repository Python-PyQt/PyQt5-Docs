.. sip:method-description::
    :status: todo
    :pysig: 46adf10cdda9e344626baf7eaf9aa4fc
    :realsig: () const
    :digest: 489d1d0cfe1db009cd4a5424033aeca2

Returns the matrix in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyTransform` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
