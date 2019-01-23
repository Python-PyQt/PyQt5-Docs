.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: a06bcdbd7092ef22e5ec403e76036208

If *enable* is true sets double buffering; otherwise sets single buffering.

Double buffering is enabled by default.

Double buffering is a technique where graphics are rendered on an off-screen buffer and not directly to the screen. When the drawing has been completed, the program calls a swapBuffers() function to exchange the screen contents with the buffer. The result is flicker-free drawing and often better performance.

Note that single buffered contexts are currently not supported with EGL.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.doubleBuffer`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.swapBuffers`, :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.swapBuffers`.
