.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: c90305e1e65d8a61f4c1e387436465b0

Set the desired *size* in bits of the green channel of the color buffer.

**Note:** On Mac OSX, be sure to set the buffer size of all color channels, otherwise this setting will have no effect. If one of the buffer sizes is not set, the current bit-depth of the screen is used.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QSurfaceFormat.greenBufferSize`.
