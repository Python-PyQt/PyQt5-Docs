.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 33eacb17e9df4f4b7579f13c94d7c8f0

Reparses the current element. This function must be called when more data becomes available in the source :sip:ref:`~PyQt5.QtCore.QIODevice` after parsing failed due to reaching the end of the input data before the end of the CBOR stream.

When reading from QByteArray(), the  function automatically calls this function. Calling it when the reading had not failed is a no-op.
