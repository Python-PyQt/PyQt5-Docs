.. sip:method-description::
    :status: todo
    :pysig: 42704ecda4a18578d2073259d8b1aa5c
    :realsig: ()
    :digest: 23234da08c16a3892512a8896892d49c

Returns the list of :sip:ref:`~PyQt5.QtCore.QStorageInfo` objects that corresponds to the list of currently mounted filesystems.

On Windows, this returns the drives visible in the **My Computer** folder. On Unix operating systems, it returns the list of all mounted filesystems (except for pseudo filesystems).

Returns all currently mounted filesystems by default.

The example shows how to retrieve all available filesystems, skipping read-only ones.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qstorageinfo.py
    :lines: 50-56

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStorageInfo.root`.
