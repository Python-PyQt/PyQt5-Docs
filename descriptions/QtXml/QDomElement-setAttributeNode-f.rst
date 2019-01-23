.. sip:method-description::
    :status: todo
    :pysig: 83e8032eaafd06da7c2e6be9fdcab162
    :realsig: (const QDomAttr&)
    :digest: 5a54f2fa690de636ee1133bb51ba041a

Adds the attribute *newAttr* to this element.

If the element has another attribute that has the same name as *newAttr*, this function replaces that attribute and returns it; otherwise the function returns a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomElement.attributeNode`, :sip:ref:`~PyQt5.QtXml.QDomElement.setAttribute`, :sip:ref:`~PyQt5.QtXml.QDomElement.setAttributeNodeNS`.
