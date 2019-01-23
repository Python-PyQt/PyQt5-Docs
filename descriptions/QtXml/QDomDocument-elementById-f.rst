.. sip:method-description::
    :status: todo
    :pysig: e4d54a5557bc4b9fc3bb0b5baa77ce24
    :realsig: (const QString&)
    :digest: 0a27e1243ef631b6e6aaedb5ee8abd0f

Returns the element whose ID is equal to *elementId*. If no element with the ID was found, this function returns a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull`.

Since the QDomClasses do not know which attributes are element IDs, this function returns always a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull`. This may change in a future version.
