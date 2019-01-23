.. sip:class-description::
    :status: todo
    :brief: Interface to report DTD content of XML data
    :digest: 43bd05be770df1a788bf8e185b37fbe2

The :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler` class provides an interface to report DTD content of XML data.

If an application needs information about notations and unparsed entities, it can implement this interface and register an instance with :sip:ref:`~PyQt5.QtXml.QXmlReader.setDTDHandler`.

Note that this interface includes only those DTD events that the XML recommendation requires processors to report, i.e. notation and unparsed entity declarations using :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler.notationDecl` and :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler.unparsedEntityDecl` respectively.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler`, `Introduction to SAX2 <https://doc.qt.io/qt-5/xml-sax.html#introduction-to-sax2>`_.
