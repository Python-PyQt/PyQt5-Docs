.. sip:method-description::
    :status: todo
    :pysig: af71d19e213335899564a956240862dd
    :realsig: (const QDBusMessage&,int) const
    :digest: 0e21050bbcddc9dd1bdf67cea6d3f7be

Sends the *message* over this connection and returns immediately. This function is suitable for method calls only. It returns an object of type :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` which can be used to track the status of the reply.

If no reply is received within *timeout* milliseconds, an automatic error will be delivered indicating the expiration of the call. The default *timeout* is -1, which will be replaced with an implementation-defined value that is suitable for inter-process communications (generally, 25 seconds). This timeout is also the upper limit for waiting in QDBusPendingCall::waitForFinished().

See the QDBusInterface::asyncCall() function for a more friendly way of placing calls.
