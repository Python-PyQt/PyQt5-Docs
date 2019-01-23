.. sip:method-description::
    :status: todo
    :pysig: c509425ef0e28e57a8206573f0d02cb6
    :realsig: (QIODevice*)
    :digest: 11cece3a9a0482df9196833f99785370

This is an overloaded function.

Returns a string that specifies the picture format of the picture read from IO device *d*, or 0 if the device cannot be read or if the format is not recognized.

Make sure that *d* is at the right position in the device (for example, at the beginning of the file).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QIODevice.pos`.
