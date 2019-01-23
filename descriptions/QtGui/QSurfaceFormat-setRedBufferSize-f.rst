.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: 3a6888f43f640bf757898b878f7e8e12

Set the desired *size* in bits of the red channel of the color buffer.

**Note:** On Mac OSX, be sure to set the buffer size of all color channels, otherwise this setting will have no effect. If one of the buffer sizes is not set, the current bit-depth of the screen is used.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QSurfaceFormat.redBufferSize`.
