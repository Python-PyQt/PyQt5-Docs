.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: b17a4620245cc2d7958351ded075a034

Set the desired *size* in bits of the blue channel of the color buffer.

**Note:** On Mac OSX, be sure to set the buffer size of all color channels, otherwise this setting will have no effect. If one of the buffer sizes is not set, the current bit-depth of the screen is used.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QSurfaceFormat.blueBufferSize`.
