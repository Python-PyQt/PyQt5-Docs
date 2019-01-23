.. sip:method-description::
    :status: todo
    :pysig: 7b92ad6b160727cb53a0bd994801f01e
    :realsig: (QDBus::CallMode,const QString&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&,const QVariant&)
    :digest: b3d50ebb8263830ce062e8741fdbedda

This is an overloaded function.

Calls the method *method* on this interface and passes the parameters to this function to the method. If *mode* is ``NoWaitForReply``, then this function will return immediately after placing the call, without waiting for a reply from the remote method. Otherwise, *mode* indicates whether this function should activate the Qt Event Loop while waiting for the reply to arrive.

This function can be used with up to 8 parameters, passed in arguments *arg1*, *arg2*, *arg3*, *arg4*, *arg5*, *arg6*, *arg7* and *arg8*. If you need more than 8 parameters or if you have a variable number of parameters to be passed, use :sip:ref:`~PyQt5.QtDBus.QDBusAbstractInterface.callWithArgumentList`.

If this function reenters the Qt event loop in order to wait for the reply, it will exclude user input. During the wait, it may deliver signals and other method calls to your application. Therefore, it must be prepared to handle a reentrancy whenever a call is placed with :sip:ref:`~PyQt5.QtDBus.QDBusAbstractInterface.call`.
