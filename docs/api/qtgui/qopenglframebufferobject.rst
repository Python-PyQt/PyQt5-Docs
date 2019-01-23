:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLFramebufferObject
    :description: QtGui/QOpenGLFramebufferObject-c.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLFramebufferObject.Attachment
        :description: QtGui/QOpenGLFramebufferObject-Attachment-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLFramebufferObject.Attachment.CombinedDepthStencil
            :description: QtGui/QOpenGLFramebufferObject-Attachment-CombinedDepthStencil-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLFramebufferObject.Attachment.Depth
            :description: QtGui/QOpenGLFramebufferObject-Attachment-Depth-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLFramebufferObject.Attachment.NoAttachment
            :description: QtGui/QOpenGLFramebufferObject-Attachment-NoAttachment-v.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLFramebufferObject.FramebufferRestorePolicy
        :description: QtGui/QOpenGLFramebufferObject-FramebufferRestorePolicy-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLFramebufferObject.FramebufferRestorePolicy.DontRestoreFramebufferBinding
            :description: QtGui/QOpenGLFramebufferObject-FramebufferRestorePolicy-DontRestoreFramebufferBinding-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLFramebufferObject.FramebufferRestorePolicy.RestoreFrameBufferBinding
            :description: QtGui/QOpenGLFramebufferObject-FramebufferRestorePolicy-RestoreFrameBufferBinding-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLFramebufferObject.FramebufferRestorePolicy.RestoreFramebufferBindingToDefault
            :description: QtGui/QOpenGLFramebufferObject-FramebufferRestorePolicy-RestoreFramebufferBindingToDefault-v.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            target: int = GL_TEXTURE_2D
        :description: QtGui/QOpenGLFramebufferObject-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat`
        :description: QtGui/QOpenGLFramebufferObject-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.__init__
        :args:
            int
            int
            target: int = GL_TEXTURE_2D
        :description: QtGui/QOpenGLFramebufferObject-__init__-f-2.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.__init__
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat`
        :description: QtGui/QOpenGLFramebufferObject-__init__-f-3.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.Attachment`
            target: int = GL_TEXTURE_2D
            internal_format: int = GL_RGBA8
        :description: QtGui/QOpenGLFramebufferObject-__init__-f-4.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.__init__
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.Attachment`
            target: int = GL_TEXTURE_2D
            internal_format: int = GL_RGBA8
        :description: QtGui/QOpenGLFramebufferObject-__init__-f-5.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.addColorAttachment
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            internal_format: int = 0
        :description: QtGui/QOpenGLFramebufferObject-addColorAttachment-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.addColorAttachment
        :args:
            int
            int
            internal_format: int = 0
        :description: QtGui/QOpenGLFramebufferObject-addColorAttachment-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.attachment
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.Attachment`
        :description: QtGui/QOpenGLFramebufferObject-attachment-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.bind
        :returns:
            bool
        :description: QtGui/QOpenGLFramebufferObject-bind-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.bindDefault
        :returns:
            bool
        :static:
        :description: QtGui/QOpenGLFramebufferObject-bindDefault-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.blitFramebuffer
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            buffers: int = GL_COLOR_BUFFER_BIT
            filter: int = GL_NEAREST
        :static:
        :description: QtGui/QOpenGLFramebufferObject-blitFramebuffer-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.blitFramebuffer
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            :sip:ref:`~PyQt5.QtCore.QRect`
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            :sip:ref:`~PyQt5.QtCore.QRect`
            buffers: int = GL_COLOR_BUFFER_BIT
            filter: int = GL_NEAREST
        :static:
        :description: QtGui/QOpenGLFramebufferObject-blitFramebuffer-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.blitFramebuffer
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            :sip:ref:`~PyQt5.QtCore.QRect`
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            :sip:ref:`~PyQt5.QtCore.QRect`
            int
            int
            int
            int
        :static:
        :description: QtGui/QOpenGLFramebufferObject-blitFramebuffer-f-2.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.blitFramebuffer
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            :sip:ref:`~PyQt5.QtCore.QRect`
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
            :sip:ref:`~PyQt5.QtCore.QRect`
            int
            int
            int
            int
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.FramebufferRestorePolicy`
        :static:
        :description: QtGui/QOpenGLFramebufferObject-blitFramebuffer-f-3.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.format
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat`
        :description: QtGui/QOpenGLFramebufferObject-format-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.handle
        :returns:
            int
        :description: QtGui/QOpenGLFramebufferObject-handle-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.hasOpenGLFramebufferBlit
        :returns:
            bool
        :static:
        :description: QtGui/QOpenGLFramebufferObject-hasOpenGLFramebufferBlit-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.hasOpenGLFramebufferObjects
        :returns:
            bool
        :static:
        :description: QtGui/QOpenGLFramebufferObject-hasOpenGLFramebufferObjects-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.height
        :returns:
            int
        :description: QtGui/QOpenGLFramebufferObject-height-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.isBound
        :returns:
            bool
        :description: QtGui/QOpenGLFramebufferObject-isBound-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.isValid
        :returns:
            bool
        :description: QtGui/QOpenGLFramebufferObject-isValid-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.release
        :returns:
            bool
        :description: QtGui/QOpenGLFramebufferObject-release-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.setAttachment
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.Attachment`
        :description: QtGui/QOpenGLFramebufferObject-setAttachment-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.size
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QOpenGLFramebufferObject-size-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.sizes
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QSize`]
        :description: QtGui/QOpenGLFramebufferObject-sizes-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.takeTexture
        :returns:
            int
        :description: QtGui/QOpenGLFramebufferObject-takeTexture-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.takeTexture
        :args:
            int
        :returns:
            int
        :description: QtGui/QOpenGLFramebufferObject-takeTexture-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.texture
        :returns:
            int
        :description: QtGui/QOpenGLFramebufferObject-texture-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.textures
        :returns:
            List[int]
        :description: QtGui/QOpenGLFramebufferObject-textures-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.toImage
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtGui/QOpenGLFramebufferObject-toImage-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.toImage
        :args:
            bool
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtGui/QOpenGLFramebufferObject-toImage-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.toImage
        :args:
            bool
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtGui/QOpenGLFramebufferObject-toImage-f-2.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLFramebufferObject.width
        :returns:
            int
        :description: QtGui/QOpenGLFramebufferObject-width-f.rst
