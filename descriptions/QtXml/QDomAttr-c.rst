.. sip:class-description::
    :status: todo
    :brief: Represents one attribute of a QDomElement
    :digest: 3e02ce02a7fac6a9a1046803087aed35

The :sip:ref:`~PyQt5.QtXml.QDomAttr` class represents one attribute of a :sip:ref:`~PyQt5.QtXml.QDomElement`.

For example, the following piece of XML produces an element with no children, but two attributes:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 123-123

You can access the attributes of an element with code like this:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 128-134

This example also shows that changing an attribute received from an element changes the attribute of the element. If you do not want to change the value of the element's attribute you must use cloneNode() to get an independent copy of the attribute.

:sip:ref:`~PyQt5.QtXml.QDomAttr` can return the :sip:ref:`~PyQt5.QtXml.QDomAttr.name` and :sip:ref:`~PyQt5.QtXml.QDomAttr.value` of an attribute. An attribute's value is set with :sip:ref:`~PyQt5.QtXml.QDomAttr.setValue`. If :sip:ref:`~PyQt5.QtXml.QDomAttr.specified` returns true the value was set with :sip:ref:`~PyQt5.QtXml.QDomAttr.setValue`. The node this attribute is attached to (if any) is returned by :sip:ref:`~PyQt5.QtXml.QDomAttr.ownerElement`.

For further information about the Document Object Model see http://www.w3.org/TR/REC-DOM-Level-1/ and http://www.w3.org/TR/DOM-Level-2-Core/. For a more general introduction of the DOM implementation see the :sip:ref:`~PyQt5.QtXml.QDomDocument` documentation.
