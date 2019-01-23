.. sip:class-description::
    :status: todo
    :brief: The XML handler classes with information about the parsing position within a file
    :digest: 122dd1593f935064e59e109716c58beb

The :sip:ref:`~PyQt5.QtXml.QXmlLocator` class provides the XML handler classes with information about the parsing position within a file.

The reader reports a :sip:ref:`~PyQt5.QtXml.QXmlLocator` to the content handler before it starts to parse the document. This is done with the :sip:ref:`~PyQt5.QtXml.QXmlContentHandler.setDocumentLocator` function. The handler classes can now use this locator to get the position (\ :sip:ref:`~PyQt5.QtXml.QXmlLocator.lineNumber` and :sip:ref:`~PyQt5.QtXml.QXmlLocator.columnNumber`) that the reader has reached.
