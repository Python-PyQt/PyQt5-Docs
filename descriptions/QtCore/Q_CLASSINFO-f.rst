.. sip:method-description::
    :status: todo
    :pysig: 4b99ff73a8a869319570237b5c57ab03
    :realsig: (const char*,const char*)
    :digest: c2466d8bae67e91574ed1711206e2a38

This macro associates extra information to the class, which is available using :sip:ref:`~PyQt5.QtCore.QObject.metaObject`. Qt makes only limited use of this feature, in the `Active Qt <https://doc.qt.io/qt-5/activeqt-index.html>`_, `Qt D-Bus <https://doc.qt.io/qt-5/qtdbus-index.html>`_ and Qt QML.

The extra information takes the form of a *Name* string and a *Value* literal string.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 374-382

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaObject.classInfo`, QAxFactory, `Using Qt D-Bus Adaptors <https://doc.qt.io/qt-5/usingadaptors.html>`_, `Extending QML <https://doc.qt.io/qt-5/qtquick-codesamples.html#extending-qml>`_.
