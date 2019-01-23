.. sip:method-description::
    :status: todo
    :pysig: b7036fdd9595c7bd0234ba6447abcc80
    :realsig: (const char*,uint)
    :digest: 2bd38232e8231863b9194fbbfc1c66e3

Writes the length specifier *len* and the buffer *s* to the stream and returns a reference to the stream.

The *len* is serialized as a quint32, followed by *len* bytes from *s*. Note that the data is *not* encoded.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDataStream.writeRawData`, :sip:ref:`~PyQt5.QtCore.QDataStream.readBytes`.
