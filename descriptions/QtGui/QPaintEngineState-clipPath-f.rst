.. sip:method-description::
    :status: todo
    :pysig: e6f793ede99782d3cd029e7921c36913
    :realsig: () const
    :digest: abfadf3eb380a235ef5d08ac5b75bf0a

Returns the clip path in the current paint engine state.

This variable should only be used when the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` returns a combination which includes the :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipPath` flag.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState`.
