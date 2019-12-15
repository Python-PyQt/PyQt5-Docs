:orphan:

.. sip:class:: PyQt5.QtQuick.QQuickWindow
    :inherits: :sip:ref:`~PyQt5.QtGui.QWindow`
    :description: QtQuick/QQuickWindow-c.rst

    .. sip:enum:: PyQt5.QtQuick.QQuickWindow.CreateTextureOption
        :description: QtQuick/QQuickWindow-CreateTextureOption-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.CreateTextureOption.TextureCanUseAtlas
            :description: QtQuick/QQuickWindow-CreateTextureOption-TextureCanUseAtlas-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.CreateTextureOption.TextureHasAlphaChannel
            :description: QtQuick/QQuickWindow-CreateTextureOption-TextureHasAlphaChannel-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.CreateTextureOption.TextureHasMipmaps
            :description: QtQuick/QQuickWindow-CreateTextureOption-TextureHasMipmaps-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.CreateTextureOption.TextureIsOpaque
            :description: QtQuick/QQuickWindow-CreateTextureOption-TextureIsOpaque-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.CreateTextureOption.TextureOwnsGLTexture
            :description: QtQuick/QQuickWindow-CreateTextureOption-TextureOwnsGLTexture-v.rst

    .. sip:enum:: PyQt5.QtQuick.QQuickWindow.NativeObjectType
        :description: QtQuick/QQuickWindow-NativeObjectType-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.NativeObjectType.NativeObjectTexture
            :description: QtQuick/QQuickWindow-NativeObjectType-NativeObjectTexture-v.rst

    .. sip:enum:: PyQt5.QtQuick.QQuickWindow.RenderStage
        :description: QtQuick/QQuickWindow-RenderStage-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.RenderStage.AfterRenderingStage
            :description: QtQuick/QQuickWindow-RenderStage-AfterRenderingStage-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.RenderStage.AfterSwapStage
            :description: QtQuick/QQuickWindow-RenderStage-AfterSwapStage-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.RenderStage.AfterSynchronizingStage
            :description: QtQuick/QQuickWindow-RenderStage-AfterSynchronizingStage-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.RenderStage.BeforeRenderingStage
            :description: QtQuick/QQuickWindow-RenderStage-BeforeRenderingStage-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.RenderStage.BeforeSynchronizingStage
            :description: QtQuick/QQuickWindow-RenderStage-BeforeSynchronizingStage-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.RenderStage.NoStage
            :description: QtQuick/QQuickWindow-RenderStage-NoStage-v.rst

    .. sip:enum:: PyQt5.QtQuick.QQuickWindow.SceneGraphError
        :description: QtQuick/QQuickWindow-SceneGraphError-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.SceneGraphError.ContextNotAvailable
            :description: QtQuick/QQuickWindow-SceneGraphError-ContextNotAvailable-v.rst

    .. sip:enum:: PyQt5.QtQuick.QQuickWindow.TextRenderType
        :description: QtQuick/QQuickWindow-TextRenderType-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.TextRenderType.NativeTextRendering
            :description: QtQuick/QQuickWindow-TextRenderType-NativeTextRendering-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickWindow.TextRenderType.QtTextRendering
            :description: QtQuick/QQuickWindow-TextRenderType-QtTextRendering-v.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtGui.QWindow` = None
        :description: QtQuick/QQuickWindow-__init__-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.activeFocusItem
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QQuickItem`
        :description: QtQuick/QQuickWindow-activeFocusItem-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.beginExternalCommands
        :description: QtQuick/QQuickWindow-beginExternalCommands-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.clearBeforeRendering
        :returns:
            bool
        :description: QtQuick/QQuickWindow-clearBeforeRendering-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.color
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtQuick/QQuickWindow-color-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.contentItem
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QQuickItem`
        :description: QtQuick/QQuickWindow-contentItem-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.createImageNode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGImageNode`
        :description: QtQuick/QQuickWindow-createImageNode-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.createRectangleNode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGRectangleNode`
        :description: QtQuick/QQuickWindow-createRectangleNode-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.createTextureFromId
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QSize`
            options: Union[:sip:ref:`~PyQt5.QtQuick.QQuickWindow.CreateTextureOptions`, :sip:ref:`~PyQt5.QtQuick.QQuickWindow.CreateTextureOption`] = QQuickWindow.CreateTextureOption()
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QQuickWindow-createTextureFromId-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.createTextureFromImage
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QQuickWindow-createTextureFromImage-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.createTextureFromImage
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
            Union[:sip:ref:`~PyQt5.QtQuick.QQuickWindow.CreateTextureOptions`, :sip:ref:`~PyQt5.QtQuick.QQuickWindow.CreateTextureOption`]
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QQuickWindow-createTextureFromImage-f-1.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.createTextureFromNativeObject
        :args:
            :sip:ref:`~PyQt5.QtQuick.QQuickWindow.NativeObjectType`
            sip.voidptr
            int
            :sip:ref:`~PyQt5.QtCore.QSize`
            options: Union[:sip:ref:`~PyQt5.QtQuick.QQuickWindow.CreateTextureOptions`, :sip:ref:`~PyQt5.QtQuick.QQuickWindow.CreateTextureOption`] = QQuickWindow.CreateTextureOption()
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QQuickWindow-createTextureFromNativeObject-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.effectiveDevicePixelRatio
        :returns:
            float
        :description: QtQuick/QQuickWindow-effectiveDevicePixelRatio-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.endExternalCommands
        :description: QtQuick/QQuickWindow-endExternalCommands-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtQuick/QQuickWindow-event-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.exposeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QExposeEvent`
        :description: QtQuick/QQuickWindow-exposeEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.focusInEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtQuick/QQuickWindow-focusInEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.focusObject
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtQuick/QQuickWindow-focusObject-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.focusOutEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtQuick/QQuickWindow-focusOutEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.grabWindow
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtQuick/QQuickWindow-grabWindow-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.hasDefaultAlphaBuffer
        :returns:
            bool
        :static:
        :description: QtQuick/QQuickWindow-hasDefaultAlphaBuffer-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.hideEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QHideEvent`
        :description: QtQuick/QQuickWindow-hideEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.incubationController
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlIncubationController`
        :description: QtQuick/QQuickWindow-incubationController-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.isPersistentOpenGLContext
        :returns:
            bool
        :description: QtQuick/QQuickWindow-isPersistentOpenGLContext-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.isPersistentSceneGraph
        :returns:
            bool
        :description: QtQuick/QQuickWindow-isPersistentSceneGraph-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.isSceneGraphInitialized
        :returns:
            bool
        :description: QtQuick/QQuickWindow-isSceneGraphInitialized-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtQuick/QQuickWindow-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.keyReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtQuick/QQuickWindow-keyReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.mouseDoubleClickEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtQuick/QQuickWindow-mouseDoubleClickEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.mouseGrabberItem
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QQuickItem`
        :description: QtQuick/QQuickWindow-mouseGrabberItem-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtQuick/QQuickWindow-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtQuick/QQuickWindow-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtQuick/QQuickWindow-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.openglContext
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtQuick/QQuickWindow-openglContext-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.releaseResources
        :description: QtQuick/QQuickWindow-releaseResources-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.rendererInterface
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGRendererInterface`
        :description: QtQuick/QQuickWindow-rendererInterface-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.renderTarget
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
        :description: QtQuick/QQuickWindow-renderTarget-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.renderTargetId
        :returns:
            int
        :description: QtQuick/QQuickWindow-renderTargetId-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.renderTargetSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtQuick/QQuickWindow-renderTargetSize-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.resetOpenGLState
        :description: QtQuick/QQuickWindow-resetOpenGLState-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtQuick/QQuickWindow-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.sceneGraphBackend
        :returns:
            str
        :static:
        :description: QtQuick/QQuickWindow-sceneGraphBackend-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.scheduleRenderJob
        :args:
            :sip:ref:`~PyQt5.QtCore.QRunnable`
            :sip:ref:`~PyQt5.QtQuick.QQuickWindow.RenderStage`
        :description: QtQuick/QQuickWindow-scheduleRenderJob-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.sendEvent
        :args:
            :sip:ref:`~PyQt5.QtQuick.QQuickItem`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtQuick/QQuickWindow-sendEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setClearBeforeRendering
        :args:
            bool
        :description: QtQuick/QQuickWindow-setClearBeforeRendering-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtQuick/QQuickWindow-setColor-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setDefaultAlphaBuffer
        :args:
            bool
        :static:
        :description: QtQuick/QQuickWindow-setDefaultAlphaBuffer-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setPersistentOpenGLContext
        :args:
            bool
        :description: QtQuick/QQuickWindow-setPersistentOpenGLContext-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setPersistentSceneGraph
        :args:
            bool
        :description: QtQuick/QQuickWindow-setPersistentSceneGraph-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setRenderTarget
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`
        :description: QtQuick/QQuickWindow-setRenderTarget-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setRenderTarget
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtQuick/QQuickWindow-setRenderTarget-f-1.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setSceneGraphBackend
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGRendererInterface.GraphicsApi`
        :static:
        :description: QtQuick/QQuickWindow-setSceneGraphBackend-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setSceneGraphBackend
        :args:
            str
        :static:
        :description: QtQuick/QQuickWindow-setSceneGraphBackend-f-1.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.setTextRenderType
        :args:
            :sip:ref:`~PyQt5.QtQuick.QQuickWindow.TextRenderType`
        :static:
        :description: QtQuick/QQuickWindow-setTextRenderType-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtQuick/QQuickWindow-showEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.textRenderType
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QQuickWindow.TextRenderType`
        :static:
        :description: QtQuick/QQuickWindow-textRenderType-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.update
        :description: QtQuick/QQuickWindow-update-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickWindow.wheelEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWheelEvent`
        :description: QtQuick/QQuickWindow-wheelEvent-f.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.activeFocusItemChanged
        :description: QtQuick/QQuickWindow-activeFocusItemChanged-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.afterAnimating
        :description: QtQuick/QQuickWindow-afterAnimating-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.afterRendering
        :description: QtQuick/QQuickWindow-afterRendering-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.afterRenderPassRecording
        :description: QtQuick/QQuickWindow-afterRenderPassRecording-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.afterSynchronizing
        :description: QtQuick/QQuickWindow-afterSynchronizing-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.beforeRendering
        :description: QtQuick/QQuickWindow-beforeRendering-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.beforeRenderPassRecording
        :description: QtQuick/QQuickWindow-beforeRenderPassRecording-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.beforeSynchronizing
        :description: QtQuick/QQuickWindow-beforeSynchronizing-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.closing
        :args:
            :sip:ref:`~PyQt5.QtQuick.QQuickCloseEvent`
        :description: QtQuick/QQuickWindow-closing-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.colorChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtQuick/QQuickWindow-colorChanged-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.frameSwapped
        :description: QtQuick/QQuickWindow-frameSwapped-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.openglContextCreated
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtQuick/QQuickWindow-openglContextCreated-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.sceneGraphAboutToStop
        :description: QtQuick/QQuickWindow-sceneGraphAboutToStop-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.sceneGraphError
        :args:
            :sip:ref:`~PyQt5.QtQuick.QQuickWindow.SceneGraphError`
            str
        :description: QtQuick/QQuickWindow-sceneGraphError-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.sceneGraphInitialized
        :description: QtQuick/QQuickWindow-sceneGraphInitialized-s.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickWindow.sceneGraphInvalidated
        :description: QtQuick/QQuickWindow-sceneGraphInvalidated-s.rst
