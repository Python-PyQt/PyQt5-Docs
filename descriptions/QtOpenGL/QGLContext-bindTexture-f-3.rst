.. sip:method-description::
    :status: todo
    :pysig: 52a52cf39c4160dfca12795b24c4d4ef
    :realsig: (const QImage&,GLenum,GLint,QGLContext::BindOptions)
    :digest: 93dbeed9b274bbfb6f2c00ae8455d6cd

Generates and binds a 2D GL texture to the current context, based on *image*. The generated texture id is returned and can be used in later ``glBindTexture()`` calls.

The *target* parameter specifies the texture target. The default target is ``GL_TEXTURE_2D``.

The *format* parameter sets the internal format for the texture. The default format is ``GL_RGBA``.

The binding *options* are a set of options used to decide how to bind the texture to the context.

The texture that is generated is cached, so multiple calls to  with the same :sip:ref:`~PyQt5.QtGui.QImage` will return the same texture id.

Note that we assume default values for the glPixelStore() and glPixelTransfer() parameters.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLContext.deleteTexture`.
