.. sip:method-description::
    :status: todo
    :pysig: 92cd2fb341e3cf6bceb424097a2e3c60
    :digest: d04711d942c6c792aa56c9a19617841c

This macro registers an enum type with the meta-object system. It must be placed after the enum declaration in a class that has the Q_OBJECT or the Q_GADGET macro. For namespaces use Q_ENUM_NS() instead.

For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 391-403

Enumerations that are declared with  have their :sip:ref:`~PyQt5.QtCore.QMetaEnum` registered in the enclosing :sip:ref:`~PyQt5.QtCore.QMetaObject`. You can also use QMetaEnum::fromType() to get the :sip:ref:`~PyQt5.QtCore.QMetaEnum`.

Registered enumerations are automatically registered also to the Qt meta type system, making them known to :sip:ref:`~PyQt5.QtCore.QMetaType` without the need to use Q_DECLARE_METATYPE(). This will enable useful features; for example, if used in a :sip:ref:`~PyQt5.QtCore.QVariant`, you can convert them to strings. Likewise, passing them to QDebug will print out their names.

.. seealso:: `Qt's Property System <https://doc.qt.io/qt-5/properties.html>`_.
