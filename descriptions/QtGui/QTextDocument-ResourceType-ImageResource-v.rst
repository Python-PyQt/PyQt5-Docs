.. sip:enum-member-description::
    :status: todo
    :value: 2
    :digest: 3f340c0decc96aa6a08bd4325b140729

The resource contains image data. Currently supported data types are :sip:ref:`~PyQt5.QtCore.QVariant.Type.Pixmap` and :sip:ref:`~PyQt5.QtCore.QVariant.Type.Image`. If the corresponding variant is of type :sip:ref:`~PyQt5.QtCore.QVariant.Type.ByteArray` then Qt attempts to load the image using :sip:ref:`~PyQt5.QtGui.QImage.loadFromData`. :sip:ref:`~PyQt5.QtCore.QVariant.Type.Icon` is currently not supported. The icon needs to be converted to one of the supported types first, for example using :sip:ref:`~PyQt5.QtGui.QIcon.pixmap`.
