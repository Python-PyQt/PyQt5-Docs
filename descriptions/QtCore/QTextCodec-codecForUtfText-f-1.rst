.. sip:method-description::
    :status: todo
    :pysig: 447e955317f479c17057c2a499db9df6
    :realsig: (const QByteArray&,QTextCodec*)
    :digest: 269afeb7a06fdc6ee679d01b8b568c83

Tries to detect the encoding of the provided snippet *ba* by using the BOM (Byte Order Mark) and returns a :sip:ref:`~PyQt5.QtCore.QTextCodec` instance that is capable of decoding the text to unicode. If the codec cannot be detected from the content provided, *defaultCodec* is returned.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForHtml`.
