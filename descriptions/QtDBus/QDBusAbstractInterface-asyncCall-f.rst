.. sip:method-description::
    :status: todo
    :pysig: 8631d79c48043d85e8f90244587724d3
    :realsig: (const QString&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&)
    :digest: 39103a98670426575c43c2f68da476a8

Calls the method *method* on this interface and passes the parameters to this function to the method.

The parameters to ``call`` are passed on to the remote function via D-Bus as input arguments. The returned :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` object can be used to find out information about the reply.

This function can be used with up to 8 parameters, passed in arguments *arg1*, *arg2*, *arg3*, *arg4*, *arg5*, *arg6*, *arg7* and *arg8*. If you need more than 8 parameters or if you have a variable number of parameters to be passed, use :sip:ref:`~PyQt5.QtDBus.QDBusAbstractInterface.asyncCallWithArgumentList`.

It can be used the following way:

.. literalinclude:: ../../../snippets/qtbase-src-dbus-doc-snippets-code-src_qdbus_qdbusabstractinterface.py
    :lines: 65-71

This example illustrates function calling with 0, 1 and 2 parameters and illustrates different parameter types passed in each (the first call to ``"ProcessWorkUnicode"`` will contain one Unicode string, the second call to ``"ProcessWork"`` will contain one string and one byte array).
