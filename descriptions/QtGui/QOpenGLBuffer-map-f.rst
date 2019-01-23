.. sip:method-description::
    :status: todo
    :pysig: e7d163738227ce0bfb6e36bd1bb1b542
    :realsig: (QOpenGLBuffer::Access)
    :digest: 128ec1f642c447b29719ce08ec71b4b4

Maps the contents of this buffer into the application's memory space and returns a pointer to it. Returns null if memory mapping is not possible. The *access* parameter indicates the type of access to be performed.

It is assumed that :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.create` has been called on this buffer and that it has been bound to the current context.

**Note:** This function is only supported under OpenGL ES 2.0 or earlier if the ``GL_OES_mapbuffer`` extension is present.

**Note:** On OpenGL ES 3.0 and newer, or, in case if desktop OpenGL, if ``GL_ARB_map_buffer_range`` is supported, this function uses ``glMapBufferRange`` instead of ``glMapBuffer``.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.unmap`, :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.create`, :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.bind`, :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.mapRange`.
