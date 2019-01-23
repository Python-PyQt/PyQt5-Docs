.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: 25d7e4b03756a1e299d8ba297366b31b

Opens a new D-Bus array suitable for appending elements of meta-type *id*.

This function is used usually in ``operator<<`` streaming operators, as in the following example:

.. literalinclude:: ../../../snippets/qtbase-src-dbus-doc-snippets-code-src_qdbus_qdbusargument.py
    :lines: 126-134

If the type you want to marshall is a QList, QVector or any of the Qt's `Container Classes <https://doc.qt.io/qt-5/containers.html>`_ that take one template parameter, you need not declare an ``operator<<`` function for it, since Qt D-Bus provides generic templates to do the job of marshalling the data. The same applies for STL's sequence containers, such as ``std::list``, ``std::vector``, etc.

.. seealso:: :sip:ref:`~PyQt5.QtDBus.QDBusArgument.endArray`, :sip:ref:`~PyQt5.QtDBus.QDBusArgument.beginStructure`, :sip:ref:`~PyQt5.QtDBus.QDBusArgument.beginMap`.
