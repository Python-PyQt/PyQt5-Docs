.. sip:method-description::
    :status: todo
    :pysig: 966a52aaac20492bc52c798b4cbfcd82
    :realsig: (const QByteArray&)
    :digest: cf63d116823237f32de7ac248ddb58c2

This is an overloaded function.

Tries to detect the encoding of the provided snippet *ba* by using the BOM (Byte Order Mark) and returns a :sip:ref:`~PyQt5.QtCore.QTextCodec` instance that is capable of decoding the text to unicode. If the codec cannot be detected, this overload returns a Latin-1 :sip:ref:`~PyQt5.QtCore.QTextCodec`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForHtml`.
