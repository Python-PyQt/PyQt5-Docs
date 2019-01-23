.. sip:method-description::
    :status: todo
    :pysig: 08353d2c8ddf4df261c70174f948e8c2
    :realsig: ()
    :digest: 07a1f38a61a9bcb4f798fc86c1c1a559

Returns a pointer to the global category ``"default"`` that is used e.g. by :sip:ref:`~PyQt5.QtCore.qDebug`, :sip:ref:`~PyQt5.QtCore.qInfo`, :sip:ref:`~PyQt5.QtCore.qWarning`, :sip:ref:`~PyQt5.QtCore.qCritical`, :sip:ref:`~PyQt5.QtCore.qFatal`.

**Note:** The returned pointer may be null during destruction of static objects.

**Note:** Ownership of the category is not transferred, do not ``delete`` the returned pointer.
