.. sip:class-description::
    :status: todo
    :brief: XML attributes
    :digest: fc7ccf6c39b9b7263140fe85b609ccc2

The :sip:ref:`~PyQt5.QtXml.QXmlAttributes` class provides XML attributes.

If attributes are reported by :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.startElement` this class is used to pass the attribute values.

Use :sip:ref:`~PyQt5.QtXml.QXmlAttributes.index` to locate the position of an attribute in the list, :sip:ref:`~PyQt5.QtXml.QXmlAttributes.count` to retrieve the number of attributes, and :sip:ref:`~PyQt5.QtXml.QXmlAttributes.clear` to remove the attributes. New attributes can be added with :sip:ref:`~PyQt5.QtXml.QXmlAttributes.append`. Use :sip:ref:`~PyQt5.QtXml.QXmlAttributes.type` to get an attribute's type and :sip:ref:`~PyQt5.QtXml.QXmlAttributes.value` to get its value. The attribute's name is available from :sip:ref:`~PyQt5.QtXml.QXmlAttributes.localName` or :sip:ref:`~PyQt5.QtXml.QXmlAttributes.qName`, and its namespace URI from :sip:ref:`~PyQt5.QtXml.QXmlAttributes.uri`.
