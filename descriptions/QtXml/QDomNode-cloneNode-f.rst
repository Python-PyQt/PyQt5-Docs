.. sip:method-description::
    :status: todo
    :pysig: 225d4dc3cbc6ac94118bcd215bc7fc44
    :realsig: (bool) const
    :digest: 5ec268a2c97954ebb750ef8176e58da6

Creates a deep (not shallow) copy of the :sip:ref:`~PyQt5.QtXml.QDomNode`.

If *deep* is true, then the cloning is done recursively which means that all the node's children are deep copied too. If *deep* is false only the node itself is copied and the copy will have no child nodes.
