.. sip:class-description::
    :status: todo
    :brief: Default implementation of all the XML handler classes
    :digest: 28b24954d3e81449731f2aae254ce7fa

The :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler` class provides a default implementation of all the XML handler classes.

This class gathers together the features of the specialized handler classes, making it a convenient starting point when implementing custom handlers for subclasses of :sip:ref:`~PyQt5.QtXml.QXmlReader`, particularly :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader`. The virtual functions from each of the base classes are reimplemented in this class, providing sensible default behavior for many common cases. By subclassing this class, and overriding these functions, you can concentrate on implementing the parts of the handler relevant to your application.

The XML reader must be told which handler to use for different kinds of events during parsing. This means that, although :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler` provides default implementations of functions inherited from all its base classes, we can still use specialized handlers for particular kinds of events.

For example, :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler` subclasses both :sip:ref:`~PyQt5.QtXml.QXmlContentHandler` and :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, so by subclassing it we can use the same handler for both of the following reader functions:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-rsslisting-listing.py
    :lines: 163-164

Since the reader will inform the handler of parsing errors, it is necessary to reimplement :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler.fatalError` if, for example, we want to stop parsing when such an error occurs:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-rsslisting-handler.py
    :lines: 186-193

The above function returns ``false``, which tells the reader to stop parsing. To continue to use the same reader, it is necessary to create a new handler instance, and set up the reader to use it in the manner described above.

It is useful to examine some of the functions inherited by :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler`, and consider why they might be reimplemented in a custom handler. Custom handlers will typically reimplement :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.startDocument` to prepare the handler for new content. Document elements and the text within them can be processed by reimplementing :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.startElement`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.endElement`, and :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.characters`. You may want to reimplement :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.endDocument` to perform some finalization or validation on the content once the document has been read completely.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler`, `Introduction to SAX2 <https://doc.qt.io/qt-5/xml-sax.html#introduction-to-sax2>`_.
