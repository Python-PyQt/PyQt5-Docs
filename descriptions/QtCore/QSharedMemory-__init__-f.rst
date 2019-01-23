.. sip:method-description::
    :status: todo
    :pysig: f3c1ea8cdc226f1c6d1536b6891b19f7
    :realsig: (QObject*)
    :digest: 62303a2834637eda5c284f0a8405870a

This function overloads :sip:ref:`~PyQt5.QtCore.QSharedMemory`.

Constructs a shared memory object with the given *parent*. The shared memory object's key is not set by the constructor, so the shared memory object does not have an underlying shared memory segment attached. The key must be set with :sip:ref:`~PyQt5.QtCore.QSharedMemory.setKey` or :sip:ref:`~PyQt5.QtCore.QSharedMemory.setNativeKey` before :sip:ref:`~PyQt5.QtCore.QSharedMemory.create` or :sip:ref:`~PyQt5.QtCore.QSharedMemory.attach` can be used.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSharedMemory.setKey`.
