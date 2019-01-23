.. sip:method-description::
    :status: todo
    :pysig: 1c5e033038cbdc4196dc8b6b6f46a61d
    :realsig: (qint64,qint64,QFileDevice::MemoryMapFlags)
    :digest: 3ddb66992eb3d9962fd6ee1ec60c681f

Maps *size* bytes of the file into memory starting at *offset*. A file should be open for a map to succeed but the file does not need to stay open after the memory has been mapped. When the :sip:ref:`~PyQt5.QtCore.QFile` is destroyed or a new file is opened with this object, any maps that have not been unmapped will automatically be unmapped.

The mapping will have the same open mode as the file (read and/or write), except when using :sip:ref:`~PyQt5.QtCore.QFileDevice.MemoryMapFlags.MapPrivateOption`, in which case it is always possible to write to the mapped memory.

Any mapping options can be passed through *flags*.

Returns a pointer to the memory or 0 if there is an error.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileDevice.unmap`.
