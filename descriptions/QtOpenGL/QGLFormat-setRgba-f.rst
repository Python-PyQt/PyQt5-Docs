.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: a9c69918fc8aedbf42c023fe10ca610a

If *enable* is true sets RGBA mode. If *enable* is false sets color index mode.

The default color mode is RGBA.

RGBA is the preferred mode for most OpenGL applications. In RGBA color mode you specify colors as red + green + blue + alpha quadruplets.

In color index mode you specify an index into a color lookup table.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.rgba`.
