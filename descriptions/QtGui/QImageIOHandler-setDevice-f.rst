.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: cbb97a7c1c84de6ac6af0297129b6059

Sets the device of the :sip:ref:`~PyQt5.QtGui.QImageIOHandler` to *device*. The image handler will use this device when reading and writing images.

The device can only be set once and must be set before calling :sip:ref:`~PyQt5.QtGui.QImageIOHandler.canRead`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler.read`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler.write`, etc. If you need to read multiple files, construct multiple instances of the appropriate :sip:ref:`~PyQt5.QtGui.QImageIOHandler` subclass.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageIOHandler.device`.
