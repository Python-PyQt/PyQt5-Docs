.. sip:method-description::
    :status: todo
    :pysig: 178de0f0e4004406294246356112f2ab
    :realsig: (const QString&,QObject*,QDBusConnection::RegisterOptions)
    :digest: 367d64f2fec45ca4a2abb0430e3a741b

Registers the object *object* at path *path* and returns ``true`` if the registration was successful. The *options* parameter specifies how much of the object *object* will be exposed through D-Bus.

This function does not replace existing objects: if there is already an object registered at path *path*, this function will return false. Use :sip:ref:`~PyQt5.QtDBus.QDBusConnection.unregisterObject` to unregister it first.

You cannot register an object as a child object of an object that was registered with QDBusConnection::ExportChildObjects.
