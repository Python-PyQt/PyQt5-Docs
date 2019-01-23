.. sip:method-description::
    :status: todo
    :pysig: 8edbba181f29adf4828a943ac14ec4d0
    :realsig: (const QDomNode&)
    :digest: 2e83cb92ca7fd82bfe95c3b560b92199

Inserts the node *newNode* in the map. If a node with the same namespace URI and the same local name already exists in the map, it is replaced by *newNode*. If the new node replaces an existing node, the replaced node is returned.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.namedItemNS`, :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.removeNamedItemNS`, :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.setNamedItem`.
