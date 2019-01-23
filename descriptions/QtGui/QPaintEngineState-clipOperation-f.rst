.. sip:method-description::
    :status: todo
    :pysig: e7b648031be59f774a2ffb1d302f9993
    :realsig: () const
    :digest: 4e1ca97d7995fa520db115add8198664

Returns the clip operation in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes either the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipPath` or the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipRegion` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
