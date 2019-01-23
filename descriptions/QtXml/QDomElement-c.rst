.. sip:class-description::
    :status: todo
    :brief: Represents one element in the DOM tree
    :digest: b87e543092fb21a44477d4197589fdf2

The :sip:ref:`~PyQt5.QtXml.QDomElement` class represents one element in the DOM tree.

Elements have a :sip:ref:`~PyQt5.QtXml.QDomElement.tagName` and zero or more attributes associated with them. The tag name can be changed with :sip:ref:`~PyQt5.QtXml.QDomElement.setTagName`.

Element attributes are represented by :sip:ref:`~PyQt5.QtXml.QDomAttr` objects that can be queried using the :sip:ref:`~PyQt5.QtXml.QDomElement.attribute` and :sip:ref:`~PyQt5.QtXml.QDomElement.attributeNode` functions. You can set attributes with the :sip:ref:`~PyQt5.QtXml.QDomElement.setAttribute` and :sip:ref:`~PyQt5.QtXml.QDomElement.setAttributeNode` functions. Attributes can be removed with :sip:ref:`~PyQt5.QtXml.QDomElement.removeAttribute`. There are namespace-aware equivalents to these functions, i.e. :sip:ref:`~PyQt5.QtXml.QDomElement.setAttributeNS`, :sip:ref:`~PyQt5.QtXml.QDomElement.setAttributeNodeNS` and :sip:ref:`~PyQt5.QtXml.QDomElement.removeAttributeNS`.

If you want to access the text of a node use :sip:ref:`~PyQt5.QtXml.QDomElement.text`, e.g.

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 139-141

The :sip:ref:`~PyQt5.QtXml.QDomElement.text` function operates recursively to find the text (since not all elements contain text). If you want to find all the text in all of a node's children, iterate over the children looking for :sip:ref:`~PyQt5.QtXml.QDomText` nodes, e.g.

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 146-153

Note that we attempt to convert each node to a text node and use :sip:ref:`~PyQt5.QtXml.QDomElement.text` rather than using firstChild().toText().`data() <https://doc.qt.io/qt-5/qtdatavisualization-qmlbars-example.html#data>`_ or n.toText().`data() <https://doc.qt.io/qt-5/qtdatavisualization-qmlbars-example.html#data>`_ directly on the node, because the node may not be a text element.

You can get a list of all the decendents of an element which have a specified tag name with :sip:ref:`~PyQt5.QtXml.QDomElement.elementsByTagName` or :sip:ref:`~PyQt5.QtXml.QDomElement.elementsByTagNameNS`.

To browse the elements of a dom document use firstChildElement(), lastChildElement(), nextSiblingElement() and previousSiblingElement(). For example, to iterate over all child elements called "entry" in a root element called "database", you can use:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 158-163

For further information about the Document Object Model see `Level 1 <https://doc.qt.io/qt-5/http://www.w3.org/TR/REC-DOM-Level-1/>`_ and `Level 2 Core <https://doc.qt.io/qt-5/http://www.w3.org/TR/DOM-Level-2-Core/>`_. For a more general introduction of the DOM implementation see the :sip:ref:`~PyQt5.QtXml.QDomDocument` documentation.
