.. sip:method-description::
    :status: todo
    :pysig: 929a782c39161405ef929c2ed8875df0
    :realsig: (const QString&,const QString&)
    :digest: 892cda3071de58ebf36811da2bec9997

Creates a new element with namespace support that can be inserted into the DOM tree. The name of the element is *qName* and the namespace URI is *nsURI*. This function also sets :sip:ref:`~PyQt5.QtXml.QDomNode.prefix` and :sip:ref:`~PyQt5.QtXml.QDomNode.localName` to appropriate values (depending on *qName*).

If *qName* is an empty string, returns a null element regardless of whether the invalid data policy is set.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomDocument.createElement`.
