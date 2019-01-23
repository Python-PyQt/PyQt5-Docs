.. sip:method-description::
    :status: todo
    :pysig: 198abce33cadc8f087d78c81b2a93eb9
    :realsig: (const QString&,const QString&) const
    :digest: d6929cd49723444390849d1f92d5456c

Returns the node associated with the local name *localName* and the namespace URI *nsURI*.

If the map does not contain such a node, a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull` is returned.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.setNamedItemNS`, :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.namedItem`.
