.. sip:method-description::
    :status: todo
    :pysig: a54f952529aeb4152bf6e488e4413b5a
    :realsig: (const QString&,const QString&,const QString&,const QString&)
    :digest: 0471a51f852d6d16b9e782de5bf28413

Constructs a new DBus message with the given *path*, *interface* and *name*, representing a signal emission to a specific destination.

A DBus signal is emitted from one application and is received only by the application owning the destination *service* name.

The :sip:ref:`~PyQt5.QtDBus.QDBusMessage` object that is returned can be sent using the QDBusConnection::send() function.
