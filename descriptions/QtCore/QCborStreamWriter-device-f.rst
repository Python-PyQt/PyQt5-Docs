.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: () const
    :digest: 3da1b10bda16cb97aea520cdb56c0469

Returns the :sip:ref:`~PyQt5.QtCore.QIODevice` that this :sip:ref:`~PyQt5.QtCore.QCborStreamWriter` object is writing to. The device must have previously been set with either the constructor or with :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.setDevice`.

If this object was created by writing to a :sip:ref:`~PyQt5.QtCore.QByteArray`, this function will return an internal instance of :sip:ref:`~PyQt5.QtCore.QBuffer`, which is owned by :sip:ref:`~PyQt5.QtCore.QCborStreamWriter`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.setDevice`.
