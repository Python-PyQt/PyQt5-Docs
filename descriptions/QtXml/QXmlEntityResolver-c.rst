.. sip:class-description::
    :status: todo
    :brief: Interface to resolve external entities contained in XML data
    :digest: 294606b438455cce0ac0a4d379c48c2c

The :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver` class provides an interface to resolve external entities contained in XML data.

If an application needs to implement customized handling for external entities, it must implement this interface, i.e. :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver.resolveEntity`, and register it with :sip:ref:`~PyQt5.QtXml.QXmlReader.setEntityResolver`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler`, `Introduction to SAX2 <https://doc.qt.io/qt-5/xml-sax.html#introduction-to-sax2>`_.
