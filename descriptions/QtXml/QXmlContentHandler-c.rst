.. sip:class-description::
    :status: todo
    :brief: Interface to report the logical content of XML data
    :digest: b7be62231274672c3096790a83250d09

The :sip:ref:`~PyQt5.QtXml.QXmlContentHandler` class provides an interface to report the logical content of XML data.

If the application needs to be informed of basic parsing events, it can implement this interface and activate it using :sip:ref:`~PyQt5.QtXml.QXmlReader.setContentHandler`. The reader can then report basic document-related events like the start and end of elements and character data through this interface.

The order of events in this interface is very important, and mirrors the order of information in the document itself. For example, all of an element's content (character data, processing instructions, and sub-elements) appears, in order, between the :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.startElement` event and the corresponding :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.endElement` event.

The class :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler` provides a default implementation for this interface; subclassing from the :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler` class is very convenient if you only want to be informed of some parsing events.

The :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.startDocument` function is called at the start of the document, and :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.endDocument` is called at the end. Before parsing begins :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.setDocumentLocator` is called. For each element :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.startElement` is called, with :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.endElement` being called at the end of each element. The :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.characters` function is called with chunks of character data; :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.ignorableWhitespace` is called with chunks of whitespace and :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.processingInstruction` is called with processing instructions. If an entity is skipped :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.skippedEntity` is called. At the beginning of prefix-URI scopes :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.startPrefixMapping` is called.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler`, :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler`, `Introduction to SAX2 <https://doc.qt.io/qt-5/xml-sax.html#introduction-to-sax2>`_.
