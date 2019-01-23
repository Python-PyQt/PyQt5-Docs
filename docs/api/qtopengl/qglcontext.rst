:orphan:

.. sip:class:: PyQt5.QtOpenGL.QGLContext
    :description: QtOpenGL/QGLContext-c.rst

    .. sip:enum:: PyQt5.QtOpenGL.QGLContext.BindOption
        :description: QtOpenGL/QGLContext-BindOption-e.rst

        .. sip:enum-member:: PyQt5.QtOpenGL.QGLContext.BindOption.DefaultBindOption
            :description: QtOpenGL/QGLContext-BindOption-DefaultBindOption-v.rst

        .. sip:enum-member:: PyQt5.QtOpenGL.QGLContext.BindOption.InvertedYBindOption
            :description: QtOpenGL/QGLContext-BindOption-InvertedYBindOption-v.rst

        .. sip:enum-member:: PyQt5.QtOpenGL.QGLContext.BindOption.LinearFilteringBindOption
            :description: QtOpenGL/QGLContext-BindOption-LinearFilteringBindOption-v.rst

        .. sip:enum-member:: PyQt5.QtOpenGL.QGLContext.BindOption.MipmapBindOption
            :description: QtOpenGL/QGLContext-BindOption-MipmapBindOption-v.rst

        .. sip:enum-member:: PyQt5.QtOpenGL.QGLContext.BindOption.NoBindOption
            :description: QtOpenGL/QGLContext-BindOption-NoBindOption-v.rst

        .. sip:enum-member:: PyQt5.QtOpenGL.QGLContext.BindOption.PremultipliedAlphaBindOption
            :description: QtOpenGL/QGLContext-BindOption-PremultipliedAlphaBindOption-v.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.__init__
        :args:
            :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`
        :description: QtOpenGL/QGLContext-__init__-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.areSharing
        :args:
            :sip:ref:`~PyQt5.QtOpenGL.QGLContext`
            :sip:ref:`~PyQt5.QtOpenGL.QGLContext`
        :returns:
            bool
        :static:
        :description: QtOpenGL/QGLContext-areSharing-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.bindTexture
        :args:
            str
        :returns:
            int
        :description: QtOpenGL/QGLContext-bindTexture-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
            target: int = GL_TEXTURE_2D
            format: int = GL_RGBA
        :returns:
            int
        :description: QtOpenGL/QGLContext-bindTexture-f-1.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            target: int = GL_TEXTURE_2D
            format: int = GL_RGBA
        :returns:
            int
        :description: QtOpenGL/QGLContext-bindTexture-f-2.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
            int
            int
            Union[:sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOptions`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOption`]
        :returns:
            int
        :description: QtOpenGL/QGLContext-bindTexture-f-3.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            int
            int
            Union[:sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOptions`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOption`]
        :returns:
            int
        :description: QtOpenGL/QGLContext-bindTexture-f-4.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.chooseContext
        :args:
            shareContext: :sip:ref:`~PyQt5.QtOpenGL.QGLContext` = None
        :returns:
            bool
        :description: QtOpenGL/QGLContext-chooseContext-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.create
        :args:
            shareContext: :sip:ref:`~PyQt5.QtOpenGL.QGLContext` = None
        :returns:
            bool
        :description: QtOpenGL/QGLContext-create-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.currentContext
        :returns:
            :sip:ref:`~PyQt5.QtOpenGL.QGLContext`
        :static:
        :description: QtOpenGL/QGLContext-currentContext-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.deleteTexture
        :args:
            int
        :description: QtOpenGL/QGLContext-deleteTexture-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.device
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPaintDevice`
        :description: QtOpenGL/QGLContext-device-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.deviceIsPixmap
        :returns:
            bool
        :description: QtOpenGL/QGLContext-deviceIsPixmap-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.doneCurrent
        :description: QtOpenGL/QGLContext-doneCurrent-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.drawTexture
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            int
            textureTarget: int = GL_TEXTURE_2D
        :description: QtOpenGL/QGLContext-drawTexture-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.drawTexture
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            int
            textureTarget: int = GL_TEXTURE_2D
        :description: QtOpenGL/QGLContext-drawTexture-f-1.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.format
        :returns:
            :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`
        :description: QtOpenGL/QGLContext-format-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.getProcAddress
        :args:
            str
        :returns:
            sip.voidptr
        :description: QtOpenGL/QGLContext-getProcAddress-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.initialized
        :returns:
            bool
        :description: QtOpenGL/QGLContext-initialized-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.isSharing
        :returns:
            bool
        :description: QtOpenGL/QGLContext-isSharing-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.isValid
        :returns:
            bool
        :description: QtOpenGL/QGLContext-isValid-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.makeCurrent
        :description: QtOpenGL/QGLContext-makeCurrent-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.moveToThread
        :args:
            :sip:ref:`~PyQt5.QtCore.QThread`
        :description: QtOpenGL/QGLContext-moveToThread-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.overlayTransparentColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtOpenGL/QGLContext-overlayTransparentColor-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.requestedFormat
        :returns:
            :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`
        :description: QtOpenGL/QGLContext-requestedFormat-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.reset
        :description: QtOpenGL/QGLContext-reset-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.setFormat
        :args:
            :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`
        :description: QtOpenGL/QGLContext-setFormat-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.setInitialized
        :args:
            bool
        :description: QtOpenGL/QGLContext-setInitialized-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.setTextureCacheLimit
        :args:
            int
        :static:
        :description: QtOpenGL/QGLContext-setTextureCacheLimit-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.setWindowCreated
        :args:
            bool
        :description: QtOpenGL/QGLContext-setWindowCreated-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.swapBuffers
        :description: QtOpenGL/QGLContext-swapBuffers-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.textureCacheLimit
        :returns:
            int
        :static:
        :description: QtOpenGL/QGLContext-textureCacheLimit-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLContext.windowCreated
        :returns:
            bool
        :description: QtOpenGL/QGLContext-windowCreated-f.rst
