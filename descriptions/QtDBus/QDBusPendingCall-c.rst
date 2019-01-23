.. sip:class-description::
    :status: todo
    :brief: Refers to one pending asynchronous call
    :digest: b41135bc876ad24af7c982b41db9f821

The :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` class refers to one pending asynchronous call.

A :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` object is a reference to a method call that was sent over D-Bus without waiting for a reply. :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` is an opaque type, meant to be used as a handle for a pending reply.

In most programs, the :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` class will not be used directly. It can be safely replaced with the template-based QDBusPendingReply, in order to access the contents of the reply or wait for it to be complete.

The :sip:ref:`~PyQt5.QtDBus.QDBusPendingCallWatcher` class allows one to connect to a signal that will indicate when the reply has arrived or if the call has timed out. It also provides the :sip:ref:`~PyQt5.QtDBus.QDBusPendingCallWatcher.waitForFinished` method which will suspend the execution of the program until the reply has arrived.

**Note:** If you create a copy of a :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` object, all information will be shared among the many copies. Therefore, :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` is an explicitly-shared object and does not provide a method of detaching the copies (since they refer to the same pending call)

.. seealso:: QDBusPendingReply, :sip:ref:`~PyQt5.QtDBus.QDBusPendingCallWatcher`, :sip:ref:`~PyQt5.QtDBus.QDBusAbstractInterface.asyncCall`.
