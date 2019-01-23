.. sip:method-description::
    :status: todo
    :pysig: 61569f2965b7a369eb10b6d75d410d11
    :realsig: (int,int)
    :digest: e61e261beef68b0f5df8cb32c91ea3cf

Opens a new D-Bus map suitable for appending elements. Maps are containers that associate one entry (the key) to another (the value), such as Qt's QMap or QHash. The ids of the map's key and value meta types must be passed in *kid* and *vid* respectively.

This function is used usually in ``operator<<`` streaming operators, as in the following example:

.. literalinclude:: ../../../snippets/qtbase-src-dbus-doc-snippets-code-src_qdbus_qdbusargument.py
    :lines: 139-150

If the type you want to marshall is a QMap or QHash, you need not declare an ``operator<<`` function for it, since Qt D-Bus provides generic templates to do the job of marshalling the data.

.. seealso:: :sip:ref:`~PyQt5.QtDBus.QDBusArgument.endMap`, :sip:ref:`~PyQt5.QtDBus.QDBusArgument.beginStructure`, :sip:ref:`~PyQt5.QtDBus.QDBusArgument.beginArray`, :sip:ref:`~PyQt5.QtDBus.QDBusArgument.beginMapEntry`.
