.. sip:method-description::
    :status: todo
    :pysig: c51f237d69882aed8b943ae3d94f1907
    :realsig: (const QString&,const QByteArray&)
    :digest: 52ba1ed77371f1e7c63b8403bce54d53

Sets the data associated with the MIME type given by *mimeType* to the specified *data*.

For the most common types of data, you can call the higher-level functions :sip:ref:`~PyQt5.QtCore.QMimeData.setText`, :sip:ref:`~PyQt5.QtCore.QMimeData.setHtml`, :sip:ref:`~PyQt5.QtCore.QMimeData.setUrls`, :sip:ref:`~PyQt5.QtCore.QMimeData.setImageData`, and :sip:ref:`~PyQt5.QtCore.QMimeData.setColorData` instead.

Note that if you want to use a custom data type in an item view drag and drop operation, you must register it as a Qt :sip:ref:`~PyQt5.QtCore.QMetaType`, using the Q_DECLARE_METATYPE() macro, and implement stream operators for it. The stream operators must then be registered with the qRegisterMetaTypeStreamOperators() function.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMimeData.data`, :sip:ref:`~PyQt5.QtCore.QMimeData.hasFormat`, :sip:ref:`~PyQt5.QtCore.QMetaType`, qRegisterMetaTypeStreamOperators().
