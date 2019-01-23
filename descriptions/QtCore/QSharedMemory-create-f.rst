.. sip:method-description::
    :status: todo
    :pysig: 6184a5851c353377633742bc4bef7a06
    :realsig: (int,QSharedMemory::AccessMode)
    :digest: 5bee0223d56303e66cfe89cbb570fbb3

Creates a shared memory segment of *size* bytes with the key passed to the constructor, set with :sip:ref:`~PyQt5.QtCore.QSharedMemory.setKey` or set with :sip:ref:`~PyQt5.QtCore.QSharedMemory.setNativeKey`, then attaches to the new shared memory segment with the given access *mode* and returns ``true``. If a shared memory segment identified by the key already exists, the attach operation is not performed and ``false`` is returned. When the return value is ``false``, call :sip:ref:`~PyQt5.QtCore.QSharedMemory.error` to determine which error occurred.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSharedMemory.error`.
