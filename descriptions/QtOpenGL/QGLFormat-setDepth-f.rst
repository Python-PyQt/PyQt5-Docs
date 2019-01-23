.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: fbeb8f3ee910649e4ce569117477793f

If *enable* is true enables the depth buffer; otherwise disables the depth buffer.

The depth buffer is enabled by default.

The purpose of a depth buffer (or Z-buffering) is to remove hidden surfaces. Pixels are assigned Z values based on the distance to the viewer. A pixel with a high Z value is closer to the viewer than a pixel with a low Z value. This information is used to decide whether to draw a pixel or not.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.depth`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDepthBufferSize`.
