.. sip:method-description::
    :status: todo
    :pysig: 59982772d69ca0dd9272e9c5213be853
    :realsig: (const QString&,const QString&,QObject*,QDBusConnection::RegisterOptions)
    :digest: ea1e4561dc5422a25428076c4d143107

This is an overloaded function.

Registers the object *object* at path *path* with interface name *interface* and returns ``true`` if the registration was successful. The *options* parameter specifies how much of the object *object* will be exposed through D-Bus.

This function does not replace existing objects: if there is already an object registered at path *path*, this function will return false. Use :sip:ref:`~PyQt5.QtDBus.QDBusConnection.unregisterObject` to unregister it first.

You cannot register an object as a child object of an object that was registered with QDBusConnection::ExportChildObjects.
