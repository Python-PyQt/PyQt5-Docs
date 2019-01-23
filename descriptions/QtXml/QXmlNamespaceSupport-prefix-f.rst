.. sip:method-description::
    :status: todo
    :pysig: 4b99ff73a8a869319570237b5c57ab03
    :realsig: (const QString&) const
    :digest: 8a01572e801b64bc8a00d451f3eb76ca

Returns one of the prefixes mapped to the namespace URI *uri*.

If more than one prefix is currently mapped to the same URI, this function makes an arbitrary selection; if you want all of the prefixes, use :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.prefixes` instead.

Note: to check for a default prefix, use the :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.uri` function with an argument of "".

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.setPrefix`.
