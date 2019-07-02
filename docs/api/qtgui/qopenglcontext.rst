:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLContext
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QOpenGLContext-c.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLContext.OpenGLModuleType
        :description: QtGui/QOpenGLContext-OpenGLModuleType-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLContext.OpenGLModuleType.LibGL
            :description: QtGui/QOpenGLContext-OpenGLModuleType-LibGL-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLContext.OpenGLModuleType.LibGLES
            :description: QtGui/QOpenGLContext-OpenGLModuleType-LibGLES-v.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QOpenGLContext-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.areSharing
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :returns:
            bool
        :static:
        :description: QtGui/QOpenGLContext-areSharing-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.create
        :returns:
            bool
        :description: QtGui/QOpenGLContext-create-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.currentContext
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :static:
        :description: QtGui/QOpenGLContext-currentContext-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.defaultFramebufferObject
        :returns:
            int
        :description: QtGui/QOpenGLContext-defaultFramebufferObject-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.doneCurrent
        :description: QtGui/QOpenGLContext-doneCurrent-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.extensions
        :returns:
            Set[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtGui/QOpenGLContext-extensions-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.format
        :returns:
            :sip:ref:`~PyQt5.QtGui.QSurfaceFormat`
        :description: QtGui/QOpenGLContext-format-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.getProcAddress
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            sip.voidptr
        :description: QtGui/QOpenGLContext-getProcAddress-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.globalShareContext
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :static:
        :description: QtGui/QOpenGLContext-globalShareContext-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.hasExtension
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            bool
        :description: QtGui/QOpenGLContext-hasExtension-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.isOpenGLES
        :returns:
            bool
        :description: QtGui/QOpenGLContext-isOpenGLES-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.isValid
        :returns:
            bool
        :description: QtGui/QOpenGLContext-isValid-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.makeCurrent
        :args:
            :sip:ref:`~PyQt5.QtGui.QSurface`
        :returns:
            bool
        :description: QtGui/QOpenGLContext-makeCurrent-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.nativeHandle
        :returns:
            Any
        :description: QtGui/QOpenGLContext-nativeHandle-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.openGLModuleHandle
        :returns:
            sip.voidptr
        :static:
        :description: QtGui/QOpenGLContext-openGLModuleHandle-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.openGLModuleType
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext.OpenGLModuleType`
        :static:
        :description: QtGui/QOpenGLContext-openGLModuleType-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.screen
        :returns:
            :sip:ref:`~PyQt5.QtGui.QScreen`
        :description: QtGui/QOpenGLContext-screen-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.setFormat
        :args:
            :sip:ref:`~PyQt5.QtGui.QSurfaceFormat`
        :description: QtGui/QOpenGLContext-setFormat-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.setNativeHandle
        :args:
            Any
        :description: QtGui/QOpenGLContext-setNativeHandle-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.setScreen
        :args:
            :sip:ref:`~PyQt5.QtGui.QScreen`
        :description: QtGui/QOpenGLContext-setScreen-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.setShareContext
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtGui/QOpenGLContext-setShareContext-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.shareContext
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtGui/QOpenGLContext-shareContext-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.shareGroup
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContextGroup`
        :description: QtGui/QOpenGLContext-shareGroup-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.supportsThreadedOpenGL
        :returns:
            bool
        :static:
        :description: QtGui/QOpenGLContext-supportsThreadedOpenGL-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.surface
        :returns:
            :sip:ref:`~PyQt5.QtGui.QSurface`
        :description: QtGui/QOpenGLContext-surface-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.swapBuffers
        :args:
            :sip:ref:`~PyQt5.QtGui.QSurface`
        :description: QtGui/QOpenGLContext-swapBuffers-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLContext.versionFunctions
        :args:
            versionProfile: :sip:ref:`~PyQt5.QtGui.QOpenGLVersionProfile` = None
        :returns:
            object
        :description: QtGui/QOpenGLContext-versionFunctions-f.rst

    .. sip:signal:: PyQt5.QtGui.QOpenGLContext.aboutToBeDestroyed
        :description: QtGui/QOpenGLContext-aboutToBeDestroyed-s.rst
