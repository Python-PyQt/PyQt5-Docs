.. sip:method-description::
    :status: todo
    :pysig: 6002a2150804a11396201b7fa936e0d4
    :realsig: (int,int,QOpenGLFramebufferObject::Attachment,GLenum,GLenum)
    :digest: 65722165000bc951dc36b38f5c1f9f48

Constructs an OpenGL framebuffer object and binds a texture to the buffer of the given *width* and *height*.

The *attachment* parameter describes the depth/stencil buffer configuration, *target* the texture target and *internalFormat* the internal texture format. The default texture target is ``GL_TEXTURE_2D``, while the default internal format is ``GL_RGBA8`` for desktop OpenGL and ``GL_RGBA`` for OpenGL/ES.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.size`, :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.texture`, :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.attachment`.
