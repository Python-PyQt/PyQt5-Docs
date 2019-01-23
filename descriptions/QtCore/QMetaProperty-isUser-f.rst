.. sip:method-description::
    :status: todo
    :pysig: 8d0068c2a9176dcc273b16acdf1a9bf0
    :realsig: (const QObject*) const
    :digest: 7b6bab28a5ee3312a703f8518e2e989d

Returns ``true`` if this property is designated as the ``USER`` property, i.e., the one that the user can edit for *object* or that is significant in some other way. Otherwise it returns false. e.g., the ``text`` property is the ``USER`` editable property of a QLineEdit.

If *object* is null, the function returns ``false`` if the ``Q_PROPERTY()``'s ``USER`` attribute is false. Otherwise it returns true.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaObject.userProperty`, :sip:ref:`~PyQt5.QtCore.QMetaProperty.isDesignable`, :sip:ref:`~PyQt5.QtCore.QMetaProperty.isScriptable`.
