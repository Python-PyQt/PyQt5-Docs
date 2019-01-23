.. sip:method-description::
    :status: todo
    :pysig: 10a3a9aef97bddb4972dc638b698aa66
    :realsig: (const QString&)
    :digest: a36cfa3bf7d79bed00ff867b160ee31d

Creates a new attribute called *name* that can be inserted into an element, e.g. using :sip:ref:`~PyQt5.QtXml.QDomElement.setAttributeNode`.

If *name* is not a valid XML name, the behavior of this function is governed by :sip:ref:`~PyQt5.QtXml.QDomImplementation.InvalidDataPolicy`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomDocument.createAttributeNS`.
