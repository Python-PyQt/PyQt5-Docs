.. sip:method-description::
    :status: todo
    :pysig: 8edbba181f29adf4828a943ac14ec4d0
    :realsig: (const QDomNode&)
    :digest: 5f128ef289301be9d755237840434561

Inserts the node *newNode* into the named node map. The name used by the map is the node name of *newNode* as returned by :sip:ref:`~PyQt5.QtXml.QDomNode.nodeName`.

If the new node replaces an existing node, i.e. the map contains a node with the same name, the replaced node is returned.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.namedItem`, :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.removeNamedItem`, :sip:ref:`~PyQt5.QtXml.QDomNamedNodeMap.setNamedItemNS`.
