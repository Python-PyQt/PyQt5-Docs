.. sip:method-description::
    :status: todo
    :pysig: 88ef868705cc2335f9e741fe200ba116
    :realsig: (const QString&,const QString&) const
    :digest: cb041f2f91c6f415d94fed916e45114d

This is an overloaded function.

Looks up an attribute's type by namespace name.

*uri* specifies the namespace URI and *localName* specifies the local name. If the name has no namespace URI, use an empty string for *uri*.

Currently only "CDATA" is returned.
