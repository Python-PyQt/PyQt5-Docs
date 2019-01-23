.. sip:class-description::
    :status: todo
    :brief: Interface to report the lexical content of XML data
    :digest: 804aa114ef5a8ded29f597bf5a90cadd

The :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler` class provides an interface to report the lexical content of XML data.

The events in the lexical handler apply to the entire document, not just to the document element, and all lexical handler events appear between the content handler's startDocument and endDocument events.

You can set the lexical handler with :sip:ref:`~PyQt5.QtXml.QXmlReader.setLexicalHandler`.

This interface's design is based on the SAX2 extension LexicalHandler.

The interface provides the :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler.startDTD`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler.endDTD`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler.startEntity`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler.endEntity`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler.startCDATA`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler.endCDATA` and :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler.comment` functions.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, `Introduction to SAX2 <https://doc.qt.io/qt-5/xml-sax.html#introduction-to-sax2>`_.
