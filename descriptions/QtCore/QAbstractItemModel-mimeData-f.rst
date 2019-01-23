.. sip:method-description::
    :status: todo
    :pysig: fb19f393911a98ef5b69d9ff655b110c
    :realsig: (const QModelIndexList&) const
    :digest: c8eeadf0464777850c0025cae0c4685d

Returns an object that contains serialized items of data corresponding to the list of *indexes* specified. The format used to describe the encoded data is obtained from the :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes` function. This default implementation uses the default MIME type returned by the default implementation of :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes`. If you reimplement :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes` in your custom model to return more MIME types, reimplement this function to make use of them.

If the list of *indexes* is empty, or there are no supported MIME types, 0 is returned rather than a serialized empty list.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.dropMimeData`.
