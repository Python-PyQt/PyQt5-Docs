.. sip:method-description::
    :status: todo
    :pysig: 92cd2fb341e3cf6bceb424097a2e3c60
    :digest: 63cca8f6aafc10403fe816461e5ab7c0

This macro registers a single flags type with the meta-object system. It is typically used in a class definition to declare that values of a given enum can be used as flags and combined using the bitwise OR operator. For namespaces use Q_FLAG_NS() instead.

The macro must be placed after the enum declaration.

For example, in :sip:ref:`~PyQt5.QtCore.QLibrary`, the LoadHints flag is declared in the following way:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 408-423

The declaration of the flags themselves is performed in the public section of the :sip:ref:`~PyQt5.QtCore.QLibrary` class itself, using the Q_DECLARE_FLAGS() macro.

**Note:** The  macro takes care of registering individual flag values with the meta-object system, so it is unnecessary to use :sip:ref:`~PyQt5.QtCore.Q_ENUM` in addition to this macro.

.. seealso:: `Qt's Property System <https://doc.qt.io/qt-5/properties.html>`_.
