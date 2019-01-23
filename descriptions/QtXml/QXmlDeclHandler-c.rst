.. sip:class-description::
    :status: todo
    :brief: Interface to report declaration content of XML data
    :digest: 7a912752c29fca4b60a2958455cad4fc

The :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler` class provides an interface to report declaration content of XML data.

You can set the declaration handler with :sip:ref:`~PyQt5.QtXml.QXmlReader.setDeclHandler`.

This interface is based on the SAX2 extension DeclHandler.

The interface provides :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler.attributeDecl`, :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler.internalEntityDecl` and :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler.externalEntityDecl` functions.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler`, `Introduction to SAX2 <https://doc.qt.io/qt-5/xml-sax.html#introduction-to-sax2>`_.
