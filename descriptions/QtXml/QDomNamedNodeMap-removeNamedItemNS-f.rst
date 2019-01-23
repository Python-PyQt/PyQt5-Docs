.. sip:method-description::
    :status: todo
    :pysig: 198abce33cadc8f087d78c81b2a93eb9
    :realsig: (const QString&,const QString&)
    :digest: 54466247ef0275c8c4d02317f0ff0557

Removes the node with the local name *localName* and the namespace URI *nsURI* from the map.

The function returns the removed node or a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull` if the map did not contain a node with the local name *localName* and the namespace URI *nsURI*.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.setNamedItemNS`, :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.namedItemNS`, :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.removeNamedItem`.
