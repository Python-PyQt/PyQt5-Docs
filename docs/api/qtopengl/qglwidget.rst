:orphan:

.. sip:class:: PyQt5.QtOpenGL.QGLWidget
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtOpenGL/QGLWidget-c.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            shareWidget: :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtOpenGL/QGLWidget-__init__-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.__init__
        :args:
            :sip:ref:`~PyQt5.QtOpenGL.QGLContext`
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            shareWidget: :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtOpenGL/QGLWidget-__init__-f-1.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.__init__
        :args:
            :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            shareWidget: :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtOpenGL/QGLWidget-__init__-f-2.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.autoBufferSwap
        :returns:
            bool
        :description: QtOpenGL/QGLWidget-autoBufferSwap-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.bindTexture
        :args:
            str
        :returns:
            int
        :description: QtOpenGL/QGLWidget-bindTexture-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
            target: int = GL_TEXTURE_2D
            format: int = GL_RGBA
        :returns:
            int
        :description: QtOpenGL/QGLWidget-bindTexture-f-1.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            target: int = GL_TEXTURE_2D
            format: int = GL_RGBA
        :returns:
            int
        :description: QtOpenGL/QGLWidget-bindTexture-f-2.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
            int
            int
            Union[:sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOptions`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOption`]
        :returns:
            int
        :description: QtOpenGL/QGLWidget-bindTexture-f-3.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.bindTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            int
            int
            Union[:sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOptions`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.BindOption`]
        :returns:
            int
        :description: QtOpenGL/QGLWidget-bindTexture-f-4.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.context
        :returns:
            :sip:ref:`~PyQt5.QtOpenGL.QGLContext`
        :description: QtOpenGL/QGLWidget-context-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.convertToGLFormat
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :static:
        :description: QtOpenGL/QGLWidget-convertToGLFormat-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.deleteTexture
        :args:
            int
        :description: QtOpenGL/QGLWidget-deleteTexture-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.doneCurrent
        :description: QtOpenGL/QGLWidget-doneCurrent-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.doubleBuffer
        :returns:
            bool
        :description: QtOpenGL/QGLWidget-doubleBuffer-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.drawTexture
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            int
            textureTarget: int = GL_TEXTURE_2D
        :description: QtOpenGL/QGLWidget-drawTexture-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.drawTexture
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            int
            textureTarget: int = GL_TEXTURE_2D
        :description: QtOpenGL/QGLWidget-drawTexture-f-1.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtOpenGL/QGLWidget-event-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.format
        :returns:
            :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`
        :description: QtOpenGL/QGLWidget-format-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.glDraw
        :description: QtOpenGL/QGLWidget-glDraw-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.glInit
        :description: QtOpenGL/QGLWidget-glInit-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.grabFrameBuffer
        :args:
            withAlpha: bool = False
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtOpenGL/QGLWidget-grabFrameBuffer-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.initializeGL
        :description: QtOpenGL/QGLWidget-initializeGL-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.initializeOverlayGL
        :description: QtOpenGL/QGLWidget-initializeOverlayGL-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.isSharing
        :returns:
            bool
        :description: QtOpenGL/QGLWidget-isSharing-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.isValid
        :returns:
            bool
        :description: QtOpenGL/QGLWidget-isValid-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.makeCurrent
        :description: QtOpenGL/QGLWidget-makeCurrent-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.makeOverlayCurrent
        :description: QtOpenGL/QGLWidget-makeOverlayCurrent-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.overlayContext
        :returns:
            :sip:ref:`~PyQt5.QtOpenGL.QGLContext`
        :description: QtOpenGL/QGLWidget-overlayContext-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.paintEngine
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPaintEngine`
        :description: QtOpenGL/QGLWidget-paintEngine-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtOpenGL/QGLWidget-paintEvent-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.paintGL
        :description: QtOpenGL/QGLWidget-paintGL-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.paintOverlayGL
        :description: QtOpenGL/QGLWidget-paintOverlayGL-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.qglClearColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtOpenGL/QGLWidget-qglClearColor-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.qglColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtOpenGL/QGLWidget-qglColor-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.renderPixmap
        :args:
            width: int = 0
            height: int = 0
            useContext: bool = False
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtOpenGL/QGLWidget-renderPixmap-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.renderText
        :args:
            int
            int
            str
            font: :sip:ref:`~PyQt5.QtGui.QFont` = QFont()
        :description: QtOpenGL/QGLWidget-renderText-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.renderText
        :args:
            float
            float
            float
            str
            font: :sip:ref:`~PyQt5.QtGui.QFont` = QFont()
        :description: QtOpenGL/QGLWidget-renderText-f-1.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtOpenGL/QGLWidget-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.resizeGL
        :args:
            int
            int
        :description: QtOpenGL/QGLWidget-resizeGL-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.resizeOverlayGL
        :args:
            int
            int
        :description: QtOpenGL/QGLWidget-resizeOverlayGL-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.setAutoBufferSwap
        :args:
            bool
        :description: QtOpenGL/QGLWidget-setAutoBufferSwap-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.setContext
        :args:
            :sip:ref:`~PyQt5.QtOpenGL.QGLContext`
            shareContext: :sip:ref:`~PyQt5.QtOpenGL.QGLContext` = None
            deleteOldContext: bool = True
        :description: QtOpenGL/QGLWidget-setContext-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.swapBuffers
        :description: QtOpenGL/QGLWidget-swapBuffers-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.updateGL
        :description: QtOpenGL/QGLWidget-updateGL-f.rst

    .. sip:method:: PyQt5.QtOpenGL.QGLWidget.updateOverlayGL
        :description: QtOpenGL/QGLWidget-updateOverlayGL-f.rst
