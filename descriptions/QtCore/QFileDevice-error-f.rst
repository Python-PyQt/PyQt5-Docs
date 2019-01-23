.. sip:method-description::
    :status: todo
    :pysig: 2a15efaf384801ed9d36e0b71fc2f011
    :realsig: () const
    :digest: 7d182d7c9a2286e464644f6cf375376c

Returns the file error status.

The I/O device status returns an error code. For example, if open() returns ``false``, or a read/write operation returns -1, this function can be called to find out the reason why the operation failed.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileDevice.unsetError`.
