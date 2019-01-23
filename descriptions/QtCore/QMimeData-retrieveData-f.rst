.. sip:method-description::
    :status: todo
    :pysig: d00bd91143d99e2fc6b1ad3a1ee18e28
    :realsig: (const QString&,QVariant::Type) const
    :digest: bc8dc3dfdaae81a09e8cdcd36a0d47d5

Returns a variant with the given *type* containing data for the MIME type specified by *mimeType*. If the object does not support the MIME type or variant type given, a null variant is returned instead.

This function is called by the general :sip:ref:`~PyQt5.QtCore.QMimeData.data` getter and by the convenience getters (\ :sip:ref:`~PyQt5.QtCore.QMimeData.text`, :sip:ref:`~PyQt5.QtCore.QMimeData.html`, :sip:ref:`~PyQt5.QtCore.QMimeData.urls`, :sip:ref:`~PyQt5.QtCore.QMimeData.imageData`, and :sip:ref:`~PyQt5.QtCore.QMimeData.colorData`). You can reimplement it if you want to store your data using a custom data structure (instead of a :sip:ref:`~PyQt5.QtCore.QByteArray`, which is what :sip:ref:`~PyQt5.QtCore.QMimeData.setData` provides). You would then also need to reimplement :sip:ref:`~PyQt5.QtCore.QMimeData.hasFormat` and :sip:ref:`~PyQt5.QtCore.QMimeData.formats`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMimeData.data`.
