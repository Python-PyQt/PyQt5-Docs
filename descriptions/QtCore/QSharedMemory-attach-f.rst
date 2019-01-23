.. sip:method-description::
    :status: todo
    :pysig: c3b11f0661b2e070c4814e0f653e062a
    :realsig: (QSharedMemory::AccessMode)
    :digest: 49c8b087c45befbd08fb530ad54bf98e

Attempts to attach the process to the shared memory segment identified by the key that was passed to the constructor or to a call to :sip:ref:`~PyQt5.QtCore.QSharedMemory.setKey` or :sip:ref:`~PyQt5.QtCore.QSharedMemory.setNativeKey`. The access *mode* is :sip:ref:`~PyQt5.QtCore.QSharedMemory.AccessMode.ReadWrite` by default. It can also be :sip:ref:`~PyQt5.QtCore.QSharedMemory.AccessMode.ReadOnly`. Returns ``true`` if the attach operation is successful. If false is returned, call :sip:ref:`~PyQt5.QtCore.QSharedMemory.error` to determine which error occurred. After attaching the shared memory segment, a pointer to the shared memory can be obtained by calling :sip:ref:`~PyQt5.QtCore.QSharedMemory.data`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSharedMemory.isAttached`, :sip:ref:`~PyQt5.QtCore.QSharedMemory.detach`, :sip:ref:`~PyQt5.QtCore.QSharedMemory.create`.
