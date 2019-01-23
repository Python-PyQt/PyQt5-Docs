.. sip:method-description::
    :status: todo
    :pysig: 1ed981e5bfe181c8ba12a5977d186452
    :realsig: (const QSize&,QOpenGLFramebufferObject::Attachment,GLenum,GLenum)
    :digest: d7b0621a145eaa6863b3be8bfdbaf711

Constructs an OpenGL framebuffer object and binds a texture to the buffer of the given *size*.

The *attachment* parameter describes the depth/stencil buffer configuration, *target* the texture target and *internalFormat* the internal texture format. The default texture target is ``GL_TEXTURE_2D``, while the default internal format is ``GL_RGBA8`` for desktop OpenGL and ``GL_RGBA`` for OpenGL/ES.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.size`, :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.texture`, :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.attachment`.
