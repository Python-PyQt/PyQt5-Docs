.. sip:class-description::
    :status: todo
    :brief: Interface to report errors in XML data
    :digest: ec13d074145d6ddd8ea26fc9c25e0a9c

The :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler` class provides an interface to report errors in XML data.

If you want your application to report errors to the user or to perform customized error handling, you should subclass this class.

You can set the error handler with :sip:ref:`~PyQt5.QtXml.QXmlReader.setErrorHandler`.

Errors can be reported using :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler.warning`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler.error` and :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler.fatalError`, with the error text being reported with :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler.errorString`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler`, `Introduction to SAX2 <https://doc.qt.io/qt-5/xml-sax.html#introduction-to-sax2>`_.
