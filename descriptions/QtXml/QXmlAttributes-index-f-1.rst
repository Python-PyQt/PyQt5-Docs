.. sip:method-description::
    :status: todo
    :pysig: ab95b36bf7c45ffa7d8e3da6a515a480
    :realsig: (const QString&,const QString&) const
    :digest: d2dc16243af85b99a97b537f2cab7399

This is an overloaded function.

Looks up the index of an attribute by a namespace name.

*uri* specifies the namespace URI, or an empty string if the name has no namespace URI. *localPart* specifies the attribute's local name.

Returns the index of the attribute, or -1 if it wasn't found.

.. seealso:: `Namespace Support via Features <https://doc.qt.io/qt-5/xml-sax.html#namespace-support-via-features>`_.
