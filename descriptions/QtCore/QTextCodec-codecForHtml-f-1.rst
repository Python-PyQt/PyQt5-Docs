.. sip:method-description::
    :status: todo
    :pysig: 447e955317f479c17057c2a499db9df6
    :realsig: (const QByteArray&,QTextCodec*)
    :digest: ee640b124e249d8752fa22fc0d659135

Tries to detect the encoding of the provided snippet of HTML in the given byte array, *ba*, by checking the BOM (Byte Order Mark) and the content-type meta header and returns a :sip:ref:`~PyQt5.QtCore.QTextCodec` instance that is capable of decoding the html to unicode. If the codec cannot be detected from the content provided, *defaultCodec* is returned.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForUtfText`.
