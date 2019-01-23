.. sip:method-description::
    :status: todo
    :pysig: e818f570a5c4413026a268d4dd70ef4b
    :realsig: (const QString&,const QList<QInputMethodEvent::Attribute>&)
    :digest: b709bfb3344d472c7e4f34dc3a15e5ac

Constructs an event of type :sip:ref:`~PyQt5.QtCore.QEvent.Type.InputMethod`. The preedit text is set to *preeditText*, the attributes to *attributes*.

The :sip:ref:`~PyQt5.QtGui.QInputMethodEvent.commitString`, :sip:ref:`~PyQt5.QtGui.QInputMethodEvent.replacementStart`, and :sip:ref:`~PyQt5.QtGui.QInputMethodEvent.replacementLength` values can be set using :sip:ref:`~PyQt5.QtGui.QInputMethodEvent.setCommitString`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QInputMethodEvent.preeditString`, :sip:ref:`~PyQt5.QtGui.QInputMethodEvent.attributes`.
