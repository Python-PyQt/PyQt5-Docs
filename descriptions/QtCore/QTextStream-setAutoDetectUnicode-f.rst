.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: 102bed3e949650b588248958d33de48a

If *enabled* is true, :sip:ref:`~PyQt5.QtCore.QTextStream` will attempt to detect Unicode encoding by peeking into the stream data to see if it can find the UTF-16 or UTF-32 BOM (Byte Order Mark). If this mark is found, :sip:ref:`~PyQt5.QtCore.QTextStream` will replace the current codec with the UTF codec.

This function can be used together with :sip:ref:`~PyQt5.QtCore.QTextStream.setCodec`. It is common to set the codec to UTF-8, and then enable UTF-16 detection.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextStream.autoDetectUnicode`, :sip:ref:`~PyQt5.QtCore.QTextStream.setCodec`.
