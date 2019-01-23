.. sip:method-description::
    :status: todo
    :pysig: a7ec19e7317ffc378dac8fb5abd6b4b0
    :realsig: (const QString&) const
    :digest: 41d749037ee82d986792002e411d2093

Returns the unique connection name of the primary owner of the name *name*. If the requested name doesn't have an owner, returns a ``org.freedesktop.DBus.Error.NameHasNoOwner`` error.
