.. sip:method-description::
    :status: todo
    :pysig: 0633dbd7bc1d5f1a40a222427ef6ce0b
    :realsig: (bool)
    :digest: 9faedf4f9a5d18f8af6b9778012dba94

Returns an image of the frame buffer. If *withAlpha* is true the alpha channel is included.

Depending on your hardware, you can explicitly select which color buffer to grab with a glReadBuffer() call before calling this function.

On QNX the back buffer is not preserved when :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.swapBuffers` is called. The back buffer where this function reads from, might thus not contain the same content as the front buffer. In order to retrieve what is currently visible on the screen, :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.swapBuffers` has to be executed prior to this function call.
