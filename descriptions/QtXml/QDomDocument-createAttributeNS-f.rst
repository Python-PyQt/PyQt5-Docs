.. sip:method-description::
    :status: todo
    :pysig: 0a06604a2213a4d8ffe0c11fa456e9ac
    :realsig: (const QString&,const QString&)
    :digest: a1c45a63371ed31277f06d54bca58f0d

Creates a new attribute with namespace support that can be inserted into an element. The name of the attribute is *qName* and the namespace URI is *nsURI*. This function also sets :sip:ref:`~PyQt5.QtXml.QDomNode.prefix` and :sip:ref:`~PyQt5.QtXml.QDomNode.localName` to appropriate values (depending on *qName*).

If *qName* is not a valid XML name, the behavior of this function is governed by :sip:ref:`~PyQt5.QtXml.QDomImplementation.InvalidDataPolicy`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomDocument.createAttribute`.
