.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: ab86d64a69ea45e61557c9950b555381

Returns the name of the node.

The meaning of the name depends on the subclass:

+---------------------------------------------------+------------------------------------------+
| Name                                              | Meaning                                  |
+===================================================+==========================================+
| :sip:ref:`~PyQt5.QtXml.QDomAttr`                  | The name of the attribute                |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomCDATASection`          | The string "#cdata-section"              |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomComment`               | The string "#comment"                    |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomDocument`              | The string "#document"                   |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomDocumentFragment`      | The string "#document-fragment"          |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomDocumentType`          | The name of the document type            |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomElement`               | The tag name                             |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomEntity`                | The name of the entity                   |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomEntityReference`       | The name of the referenced entity        |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomNotation`              | The name of the notation                 |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomProcessingInstruction` | The target of the processing instruction |
+---------------------------------------------------+------------------------------------------+
| :sip:ref:`~PyQt5.QtXml.QDomText`                  | The string "#text"                       |
+---------------------------------------------------+------------------------------------------+

**Note:** This function does not take the presence of namespaces into account when processing the names of element and attribute nodes. As a result, the returned name can contain any namespace prefix that may be present. To obtain the node name of an element or attribute, use :sip:ref:`~PyQt5.QtXml.QDomNode.localName`; to obtain the namespace prefix, use :sip:ref:`~PyQt5.QtXml.QDomNode.namespaceURI`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.nodeValue`.
