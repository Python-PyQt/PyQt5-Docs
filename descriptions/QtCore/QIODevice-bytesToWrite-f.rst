.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: a8776c8df5319adbc9086460c558c49c

For buffered devices, this function returns the number of bytes waiting to be written. For devices with no buffer, this function returns 0.

Subclasses that reimplement this function must call the base implementation in order to include the size of the buffer of :sip:ref:`~PyQt5.QtCore.QIODevice`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QIODevice.bytesAvailable`, :sip:ref:`~PyQt5.QtCore.QIODevice.bytesWritten`, :sip:ref:`~PyQt5.QtCore.QIODevice.isSequential`.
