.. sip:method-description::
    :status: todo
    :pysig: 2f43b42fd833d1e77420a8dae7419000
    :realsig: (PyObject *)
    :digest: 05af30714ae7a28783b244ac57928f50

This macro registers one or several flags types with the meta-object system. It is typically used in a class definition to declare that values of a given enum can be used as flags and combined using the bitwise OR operator.

**Note:** This macro takes care of registering individual flag values with the meta-object system, so it is unnecessary to use :sip:ref:`~PyQt5.QtCore.Q_ENUMS` in addition to this macro.

In new code, you should prefer the use of the :sip:ref:`~PyQt5.QtCore.Q_FLAG` macro, which makes the type available also to the meta type system.

.. seealso:: `Qt's Property System <https://doc.qt.io/qt-5/properties.html>`_.
