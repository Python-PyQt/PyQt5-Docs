.. sip:method-description::
    :status: todo
    :pysig: a54f952529aeb4152bf6e488e4413b5a
    :realsig: (const QString&,const QString&,const QString&,const QString&)
    :digest: ca41c6b64906a8bf36aad198925d8294

Constructs a new DBus message representing a method call. A method call always informs its destination address (\ *service*, *path*, *interface* and *method*).

The DBus bus allows calling a method on a given remote object without specifying the destination interface, if the method name is unique. However, if two interfaces on the remote object export the same method name, the result is undefined (one of the two may be called or an error may be returned).

When using DBus in a peer-to-peer context (i.e., not on a bus), the *service* parameter is optional.

The :sip:ref:`~PyQt5.QtDBus.QDBusInterface` class provides a simpler abstraction to synchronous method calling.

This function returns a :sip:ref:`~PyQt5.QtDBus.QDBusMessage` object that can be sent with QDBusConnection::call().
