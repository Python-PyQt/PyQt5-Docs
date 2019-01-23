.. sip:method-description::
    :status: todo
    :pysig: 966a52aaac20492bc52c798b4cbfcd82
    :realsig: (const QByteArray&)
    :digest: f940a6b7224564f3775198ac1c88f0a4

This is an overloaded function.

Tries to detect the encoding of the provided snippet of HTML in the given byte array, *ba*, by checking the BOM (Byte Order Mark) and the content-type meta header and returns a :sip:ref:`~PyQt5.QtCore.QTextCodec` instance that is capable of decoding the html to unicode. If the codec cannot be detected, this overload returns a Latin-1 :sip:ref:`~PyQt5.QtCore.QTextCodec`.
