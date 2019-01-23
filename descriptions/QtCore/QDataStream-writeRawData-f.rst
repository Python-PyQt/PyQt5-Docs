.. sip:method-description::
    :status: todo
    :pysig: 1512a78beed0c522a2fd3dcdf28d9ecd
    :realsig: (const char*,int)
    :digest: e36969a221dc0af9251eb7f895d99ab3

Writes *len* bytes from *s* to the stream. Returns the number of bytes actually written, or -1 on error. The data is *not* encoded.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDataStream.writeBytes`, :sip:ref:`~PyQt5.QtCore.QIODevice.write`, :sip:ref:`~PyQt5.QtCore.QDataStream.readRawData`.
