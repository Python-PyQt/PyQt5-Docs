.. sip:class-description::
    :status: todo
    :brief: XML writer with a simple streaming API
    :digest: 002ba50d81c110e8c3dcc7d2d50348e0

The :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter` class provides an XML writer with a simple streaming API.

:sip:ref:`~PyQt5.QtCore.QXmlStreamWriter` is the counterpart to :sip:ref:`~PyQt5.QtCore.QXmlStreamReader` for writing XML. Like its related class, it operates on a :sip:ref:`~PyQt5.QtCore.QIODevice` specified with :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.setDevice`. The API is simple and straightforward: for every XML token or event you want to write, the writer provides a specialized function.

You start a document with :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeStartDocument` and end it with :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeEndDocument`. This will implicitly close all remaining open tags.

Element tags are opened with :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeStartElement` followed by :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeAttribute` or :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeAttributes`, element content, and then :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeEndElement`. A shorter form :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeEmptyElement` can be used to write empty elements, followed by :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeAttributes`.

Element content consists of either characters, entity references or nested elements. It is written with :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeCharacters`, which also takes care of escaping all forbidden characters and character sequences, :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeEntityReference`, or subsequent calls to :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeStartElement`. A convenience method :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeTextElement` can be used for writing terminal elements that contain nothing but text.

The following abridged code snippet shows the basic use of the class to write formatted XML with indentation:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qxmlstreamwriter-main.py
    :lines: 65-67

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qxmlstreamwriter-main.py
    :lines: 75-78

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qxmlstreamwriter-main.py
    :lines: 83-83

:sip:ref:`~PyQt5.QtCore.QXmlStreamWriter` takes care of prefixing namespaces, all you have to do is specify the ``namespaceUri`` when writing elements or attributes. If you must conform to certain prefixes, you can force the writer to use them by declaring the namespaces manually with either :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeNamespace` or :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeDefaultNamespace`. Alternatively, you can bypass the stream writer's namespace support and use overloaded methods that take a qualified name instead. The namespace *http://www.w3.org/XML/1998/namespace* is implicit and mapped to the prefix *xml*.

The stream writer can automatically format the generated XML data by adding line-breaks and indentation to empty sections between elements, making the XML data more readable for humans and easier to work with for most source code management systems. The feature can be turned on with the :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.autoFormatting` property, and customized with the :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.autoFormattingIndent` property.

Other functions are :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeCDATA`, :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeComment`, :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeProcessingInstruction`, and :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeDTD`. Chaining of XML streams is supported with :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeCurrentToken`.

By default, :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter` encodes XML in UTF-8. Different encodings can be enforced using :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.setCodec`.

If an error occurs while writing to the underlying device, :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.hasError` starts returning true and subsequent writes are ignored.

The `QXmlStream Bookmarks Example <https://doc.qt.io/qt-5/qtxml-streambookmarks-example.html>`_ illustrates how to use a stream writer to write an XML bookmark file (XBEL) that was previously read in by a :sip:ref:`~PyQt5.QtCore.QXmlStreamReader`.
