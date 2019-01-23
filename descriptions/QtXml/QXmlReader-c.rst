.. sip:class-description::
    :status: todo
    :brief: Interface for XML readers (i.e. parsers)
    :digest: 2f1f48f7f94dc05e2805c7437b6e9a5b

The :sip:ref:`~PyQt5.QtXml.QXmlReader` class provides an interface for XML readers (i.e. parsers).

This abstract class provides an interface for all of Qt's XML readers. Currently there is only one implementation of a reader included in Qt's XML module: :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader`. In future releases there might be more readers with different properties available (e.g. a validating parser).

The design of the XML classes follows the `SAX2 Java interface <https://doc.qt.io/qt-5/http://www.saxproject.org/>`_, with the names adapted to fit Qt naming conventions. It should be very easy for anybody who has worked with SAX2 to get started with the Qt XML classes.

All readers use the class :sip:ref:`~PyQt5.QtXml.QXmlInputSource` to read the input document. Since you are normally interested in particular content in the XML document, the reader reports the content through special handler classes (\ :sip:ref:`~PyQt5.QtXml.QXmlDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlDeclHandler`, :sip:ref:`~PyQt5.QtXml.QXmlContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler` and :sip:ref:`~PyQt5.QtXml.QXmlLexicalHandler`), which you must subclass, if you want to process the contents.

Since the handler classes only describe interfaces you must implement all the functions. We provide the :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler` class to make this easier: it implements a default behavior (do nothing) for all functions, so you can subclass it and just implement the functions you are interested in.

Features and properties of the reader can be set with :sip:ref:`~PyQt5.QtXml.QXmlReader.setFeature` and :sip:ref:`~PyQt5.QtXml.QXmlReader.setProperty` respectively. You can set the reader to use your own subclasses with :sip:ref:`~PyQt5.QtXml.QXmlReader.setEntityResolver`, :sip:ref:`~PyQt5.QtXml.QXmlReader.setDTDHandler`, :sip:ref:`~PyQt5.QtXml.QXmlReader.setContentHandler`, :sip:ref:`~PyQt5.QtXml.QXmlReader.setErrorHandler`, :sip:ref:`~PyQt5.QtXml.QXmlReader.setLexicalHandler` and :sip:ref:`~PyQt5.QtXml.QXmlReader.setDeclHandler`. The parse itself is started with a call to :sip:ref:`~PyQt5.QtXml.QXmlReader.parse`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader`.
