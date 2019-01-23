.. sip:method-description::
    :status: todo
    :pysig: 0a9fd02b73b00a84b844e2029b59c962
    :realsig: () const
    :digest: a18254ff2e4dfe4e52ecf71462b848fd

Returns the clip region in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipRegion` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
