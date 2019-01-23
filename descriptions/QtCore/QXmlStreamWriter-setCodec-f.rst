.. sip:method-description::
    :status: todo
    :pysig: 46cd985fa7d56568c797b08fdc42071c
    :realsig: (QTextCodec*)
    :digest: da5be27a8f213908fbdf6c96aab21110

Sets the codec for this stream to *codec*. The codec is used for encoding any data that is written. By default, :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter` uses UTF-8.

The encoding information is stored in the initial xml tag which gets written when you call :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeStartDocument`. Call this function before calling :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.writeStartDocument`.

**Note:** When writing the XML to a QString, the codec information is ignored and the XML header will not include any encoding information, since all QStrings are UTF-16. If you later convert the QString to an 8-bit format, you must arrange for the encoding information to be transmitted out-of-band.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter.codec`.
