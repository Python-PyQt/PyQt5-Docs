.. sip:method-description::
    :status: todo
    :pysig: 46cd985fa7d56568c797b08fdc42071c
    :realsig: (QTextCodec*)
    :digest: 2c02cc0c337d4fc0cae9f8558fa58afd

Sets the codec for this stream to *codec*. The codec is used for decoding any data that is read from the assigned device, and for encoding any data that is written. By default, :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForLocale` is used, and automatic unicode detection is enabled.

If :sip:ref:`~PyQt5.QtCore.QTextStream` operates on a string, this function does nothing.

**Warning:** If you call this function while the text stream is reading from an open sequential socket, the internal buffer may still contain text decoded using the old codec.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextStream.codec`, :sip:ref:`~PyQt5.QtCore.QTextStream.setAutoDetectUnicode`, :sip:ref:`~PyQt5.QtCore.QTextStream.setLocale`.
