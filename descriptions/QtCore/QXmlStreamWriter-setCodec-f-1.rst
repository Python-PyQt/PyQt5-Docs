.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const char*)
    :digest: 5e760c6de54f2a16c45f22de7432fcbe

Sets the codec for this stream to the :sip:ref:`~PyQt5.QtCore.QTextCodec` for the encoding specified by *codecName*. Common values for ``codecName`` include "ISO 8859-1", "UTF-8", and "UTF-16". If the encoding isn't recognized, nothing happens.

**Note:** When writing the XML to a QString, the codec information is ignored and the XML header will not include any encoding information, since all QStrings are UTF-16. If you later convert the QString to an 8-bit format, you must arrange for the encoding information to be transmitted out-of-band.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForName`.
