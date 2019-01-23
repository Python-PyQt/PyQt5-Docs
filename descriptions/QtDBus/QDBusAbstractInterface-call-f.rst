.. sip:method-description::
    :status: todo
    :pysig: 9f6d2ff78bde23012862319b1af4b055
    :realsig: (const QString&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&)
    :digest: 02025489513b6d52c2aea0664b2e6ce4

Calls the method *method* on this interface and passes the parameters to this function to the method.

The parameters to ``call`` are passed on to the remote function via D-Bus as input arguments. Output arguments are returned in the :sip:ref:`~PyQt5.QtDBus.QDBusMessage` reply. If the reply is an error reply, :sip:ref:`~PyQt5.QtDBus.QDBusAbstractInterface.lastError` will also be set to the contents of the error message.

This function can be used with up to 8 parameters, passed in arguments *arg1*, *arg2*, *arg3*, *arg4*, *arg5*, *arg6*, *arg7* and *arg8*. If you need more than 8 parameters or if you have a variable number of parameters to be passed, use :sip:ref:`~PyQt5.QtDBus.QDBusAbstractInterface.callWithArgumentList`.

It can be used the following way:

.. literalinclude:: ../../../snippets/qtbase-src-dbus-doc-snippets-code-src_qdbus_qdbusabstractinterface.py
    :lines: 54-61

This example illustrates function calling with 0, 1 and 2 parameters and illustrates different parameter types passed in each (the first call to ``"ProcessWorkUnicode"`` will contain one Unicode string, the second call to ``"ProcessWork"`` will contain one string and one byte array).
