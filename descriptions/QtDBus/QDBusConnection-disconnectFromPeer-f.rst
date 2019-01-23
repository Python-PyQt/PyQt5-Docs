.. sip:method-description::
    :status: todo
    :pysig: 49cd6c4846645627c7c8750fdcfb2bfd
    :realsig: (const QString&)
    :digest: e060389f6f4df4b0ec1733ab0cbd5b83

Closes the peer connection of name *name*.

Note that if there are still :sip:ref:`~PyQt5.QtDBus.QDBusConnection` objects associated with the same connection, the connection will not be closed until all references are dropped. However, no further references can be created using the :sip:ref:`~PyQt5.QtDBus.QDBusConnection` constructor.
