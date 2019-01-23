.. sip:method-description::
    :status: todo
    :pysig: 83e8032eaafd06da7c2e6be9fdcab162
    :realsig: (const QDomAttr&)
    :digest: 70ad05db249c88c5280a6751c895a5a6

Adds the attribute *newAttr* to this element.

If the element has another attribute that has the same local name and namespace URI as *newAttr*, this function replaces that attribute and returns it; otherwise the function returns a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomElement.attributeNodeNS`, :sip:ref:`~PyQt5.QtXml.QDomElement.setAttributeNS`, :sip:ref:`~PyQt5.QtXml.QDomElement.setAttributeNode`.
