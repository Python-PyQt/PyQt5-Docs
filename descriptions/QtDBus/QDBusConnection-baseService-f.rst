.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: acd8c05a2e66722d8387afa7514eab78

Returns the unique connection name for this connection, if this :sip:ref:`~PyQt5.QtDBus.QDBusConnection` object is connected, or an empty QString otherwise.

A Unique Connection Name is a string in the form ":x.xxx" (where x are decimal digits) that is assigned by the D-Bus server daemon upon connection. It uniquely identifies this client in the bus.

This function returns an empty QString for peer-to-peer connections.
