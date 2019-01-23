.. sip:class-description::
    :status: todo
    :brief: Implementation of a simple XML parser
    :digest: 08c86904779cf0db56eb81be97f93faf

The :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader` class provides an implementation of a simple XML parser.

This XML reader is suitable for a wide range of applications. It is able to parse well-formed XML and can report the namespaces of elements to a content handler; however, it does not parse any external entities. For historical reasons, Attribute Value Normalization and End-of-Line Handling as described in the XML 1.0 specification is not performed.

The easiest pattern of use for this class is to create a reader instance, define an input source, specify the handlers to be used by the reader, and parse the data.

For example, we could use a :sip:ref:`~PyQt5.QtCore.QFile` to supply the input. Here, we create a reader, and define an input source to be used by the reader:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-simpleparse-main.py
    :lines: 69-70

A handler lets us perform actions when the reader encounters certain types of content, or if errors in the input are found. The reader must be told which handler to use for each type of event. For many common applications, we can create a custom handler by subclassing :sip:ref:`~PyQt5.QtXml.QXmlDefaultHandler`, and use this to handle both error and content events:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-simpleparse-main.py
    :lines: 74-76

If you don't set at least the content and error handlers, the parser will fall back on its default behavior---and will do nothing.

The most convenient way to handle the input is to read it in a single pass using the :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parse` function with an argument that specifies the input source:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-simpleparse-main.py
    :lines: 80-83

If you can't parse the entire input in one go (for example, it is huge, or is being delivered over a network connection), data can be fed to the parser in pieces. This is achieved by telling :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parse` to work incrementally, and making subsequent calls to the :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parseContinue` function, until all the data has been processed.

A common way to perform incremental parsing is to connect the ``readyRead()`` signal of a :sip:ref:`~PyQt5.QtNetwork.QNetworkReply` a slot, and handle the incoming data there. See :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager`.

Aspects of the parsing behavior can be adapted using :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.setFeature` and :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.setProperty`.

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_sax_qxml.py
    :lines: 54-54

:sip:ref:`~PyQt5.QtXml.QXmlSimpleReader` is not reentrant. If you want to use the class in threaded code, lock the code using :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader` with a locking mechanism, such as a :sip:ref:`~PyQt5.QtCore.QMutex`.
