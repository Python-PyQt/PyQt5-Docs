.. sip:method-description::
    :status: todo
    :pysig: 49cd6c4846645627c7c8750fdcfb2bfd
    :realsig: (const QString&)
    :digest: 08b2fecf3903b806f483e16e72bc8a77

Closes the bus connection of name *name*.

Note that if there are still :sip:ref:`~PyQt5.QtDBus.QDBusConnection` objects associated with the same connection, the connection will not be closed until all references are dropped. However, no further references can be created using the :sip:ref:`~PyQt5.QtDBus.QDBusConnection` constructor.
