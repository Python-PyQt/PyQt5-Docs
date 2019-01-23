.. sip:method-description::
    :status: todo
    :pysig: 2f43b42fd833d1e77420a8dae7419000
    :realsig: (PyObject *)
    :digest: 38970586132fa46ccd961f96cff64d1b

This macro registers one or several enum types to the meta-object system.

For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 391-403

If you want to register an enum that is declared in another class, the enum must be fully qualified with the name of the class defining it. In addition, the class *defining* the enum has to inherit :sip:ref:`~PyQt5.QtCore.QObject` as well as declare the enum using .

In new code, you should prefer the use of the :sip:ref:`~PyQt5.QtCore.Q_ENUM` macro, which makes the type available also to the meta type system. For instance, QMetaEnum::fromType() will not work with types declared with .

.. seealso:: `Qt's Property System <https://doc.qt.io/qt-5/properties.html>`_.
