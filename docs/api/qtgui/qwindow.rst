:orphan:

.. sip:class:: PyQt5.QtGui.QWindow
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject` :sip:ref:`~PyQt5.QtGui.QSurface`
    :description: QtGui/QWindow-c.rst

    .. sip:enum:: PyQt5.QtGui.QWindow.AncestorMode
        :description: QtGui/QWindow-AncestorMode-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.AncestorMode.ExcludeTransients
            :description: QtGui/QWindow-AncestorMode-ExcludeTransients-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.AncestorMode.IncludeTransients
            :description: QtGui/QWindow-AncestorMode-IncludeTransients-v.rst

    .. sip:enum:: PyQt5.QtGui.QWindow.Visibility
        :description: QtGui/QWindow-Visibility-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.Visibility.AutomaticVisibility
            :description: QtGui/QWindow-Visibility-AutomaticVisibility-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.Visibility.FullScreen
            :description: QtGui/QWindow-Visibility-FullScreen-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.Visibility.Hidden
            :description: QtGui/QWindow-Visibility-Hidden-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.Visibility.Maximized
            :description: QtGui/QWindow-Visibility-Maximized-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.Visibility.Minimized
            :description: QtGui/QWindow-Visibility-Minimized-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QWindow.Visibility.Windowed
            :description: QtGui/QWindow-Visibility-Windowed-v.rst

    .. sip:method:: PyQt5.QtGui.QWindow.__init__
        :args:
            screen: :sip:ref:`~PyQt5.QtGui.QScreen` = None
        :description: QtGui/QWindow-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtGui/QWindow-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QWindow.alert
        :args:
            int
        :description: QtGui/QWindow-alert-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.baseSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-baseSize-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.close
        :returns:
            bool
        :description: QtGui/QWindow-close-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.contentOrientation
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QWindow-contentOrientation-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.create
        :description: QtGui/QWindow-create-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.cursor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QCursor`
        :description: QtGui/QWindow-cursor-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.destroy
        :description: QtGui/QWindow-destroy-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.devicePixelRatio
        :returns:
            float
        :description: QtGui/QWindow-devicePixelRatio-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtGui/QWindow-event-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.exposeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QExposeEvent`
        :description: QtGui/QWindow-exposeEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.filePath
        :returns:
            str
        :description: QtGui/QWindow-filePath-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.flags
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`
        :description: QtGui/QWindow-flags-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.focusInEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtGui/QWindow-focusInEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.focusObject
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtGui/QWindow-focusObject-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.focusOutEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtGui/QWindow-focusOutEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.format
        :returns:
            :sip:ref:`~PyQt5.QtGui.QSurfaceFormat`
        :description: QtGui/QWindow-format-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.frameGeometry
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QWindow-frameGeometry-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.frameMargins
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMargins`
        :description: QtGui/QWindow-frameMargins-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.framePosition
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QWindow-framePosition-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.fromWinId
        :args:
            sip.voidptr
        :returns:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtGui/QWindow-fromWinId-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.geometry
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QWindow-geometry-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.height
        :returns:
            int
        :description: QtGui/QWindow-height-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.hide
        :description: QtGui/QWindow-hide-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.hideEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QHideEvent`
        :description: QtGui/QWindow-hideEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.icon
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtGui/QWindow-icon-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.isActive
        :returns:
            bool
        :description: QtGui/QWindow-isActive-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.isAncestorOf
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            mode: :sip:ref:`~PyQt5.QtGui.QWindow.AncestorMode` = :sip:ref:`~PyQt5.QtGui.QWindow.AncestorMode.IncludeTransients`
        :returns:
            bool
        :description: QtGui/QWindow-isAncestorOf-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.isExposed
        :returns:
            bool
        :description: QtGui/QWindow-isExposed-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.isModal
        :returns:
            bool
        :description: QtGui/QWindow-isModal-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.isTopLevel
        :returns:
            bool
        :description: QtGui/QWindow-isTopLevel-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.isVisible
        :returns:
            bool
        :description: QtGui/QWindow-isVisible-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtGui/QWindow-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.keyReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtGui/QWindow-keyReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.lower
        :description: QtGui/QWindow-lower-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.mapFromGlobal
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QWindow-mapFromGlobal-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.mapToGlobal
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QWindow-mapToGlobal-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.mask
        :returns:
            :sip:ref:`~PyQt5.QtGui.QRegion`
        :description: QtGui/QWindow-mask-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.maximumHeight
        :returns:
            int
        :description: QtGui/QWindow-maximumHeight-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.maximumSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-maximumSize-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.maximumWidth
        :returns:
            int
        :description: QtGui/QWindow-maximumWidth-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.minimumHeight
        :returns:
            int
        :description: QtGui/QWindow-minimumHeight-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.minimumSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-minimumSize-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.minimumWidth
        :returns:
            int
        :description: QtGui/QWindow-minimumWidth-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.modality
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowModality`
        :description: QtGui/QWindow-modality-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.mouseDoubleClickEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtGui/QWindow-mouseDoubleClickEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtGui/QWindow-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtGui/QWindow-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtGui/QWindow-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.moveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMoveEvent`
        :description: QtGui/QWindow-moveEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.opacity
        :returns:
            float
        :description: QtGui/QWindow-opacity-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.parent
        :returns:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtGui/QWindow-parent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.parent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow.AncestorMode`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtGui/QWindow-parent-f-1.rst

    .. sip:method:: PyQt5.QtGui.QWindow.position
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QWindow-position-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.raise_
        :description: QtGui/QWindow-raise_-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.reportContentOrientationChange
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QWindow-reportContentOrientationChange-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.requestActivate
        :description: QtGui/QWindow-requestActivate-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.requestedFormat
        :returns:
            :sip:ref:`~PyQt5.QtGui.QSurfaceFormat`
        :description: QtGui/QWindow-requestedFormat-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.requestUpdate
        :description: QtGui/QWindow-requestUpdate-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.resize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-resize-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.resize
        :args:
            int
            int
        :description: QtGui/QWindow-resize-f-1.rst

    .. sip:method:: PyQt5.QtGui.QWindow.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtGui/QWindow-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.screen
        :returns:
            :sip:ref:`~PyQt5.QtGui.QScreen`
        :description: QtGui/QWindow-screen-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setBaseSize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-setBaseSize-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setCursor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QCursor`, :sip:ref:`~PyQt5.QtCore.Qt.CursorShape`]
        :description: QtGui/QWindow-setCursor-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setFilePath
        :args:
            str
        :description: QtGui/QWindow-setFilePath-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setFlag
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowType`
            on: bool = True
        :description: QtGui/QWindow-setFlag-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setFlags
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`]
        :description: QtGui/QWindow-setFlags-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setFormat
        :args:
            :sip:ref:`~PyQt5.QtGui.QSurfaceFormat`
        :description: QtGui/QWindow-setFormat-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setFramePosition
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QWindow-setFramePosition-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setGeometry
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QWindow-setGeometry-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setGeometry
        :args:
            int
            int
            int
            int
        :description: QtGui/QWindow-setGeometry-f-1.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setHeight
        :args:
            int
        :description: QtGui/QWindow-setHeight-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setIcon
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtGui/QWindow-setIcon-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setKeyboardGrabEnabled
        :args:
            bool
        :returns:
            bool
        :description: QtGui/QWindow-setKeyboardGrabEnabled-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMask
        :args:
            :sip:ref:`~PyQt5.QtGui.QRegion`
        :description: QtGui/QWindow-setMask-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMaximumHeight
        :args:
            int
        :description: QtGui/QWindow-setMaximumHeight-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMaximumSize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-setMaximumSize-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMaximumWidth
        :args:
            int
        :description: QtGui/QWindow-setMaximumWidth-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMinimumHeight
        :args:
            int
        :description: QtGui/QWindow-setMinimumHeight-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMinimumSize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-setMinimumSize-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMinimumWidth
        :args:
            int
        :description: QtGui/QWindow-setMinimumWidth-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setModality
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowModality`
        :description: QtGui/QWindow-setModality-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setMouseGrabEnabled
        :args:
            bool
        :returns:
            bool
        :description: QtGui/QWindow-setMouseGrabEnabled-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setOpacity
        :args:
            float
        :description: QtGui/QWindow-setOpacity-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setParent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtGui/QWindow-setParent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setPosition
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QWindow-setPosition-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setPosition
        :args:
            int
            int
        :description: QtGui/QWindow-setPosition-f-1.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setScreen
        :args:
            :sip:ref:`~PyQt5.QtGui.QScreen`
        :description: QtGui/QWindow-setScreen-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setSizeIncrement
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-setSizeIncrement-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setSurfaceType
        :args:
            :sip:ref:`~PyQt5.QtGui.QSurface.SurfaceType`
        :description: QtGui/QWindow-setSurfaceType-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setTitle
        :args:
            str
        :description: QtGui/QWindow-setTitle-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setTransientParent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtGui/QWindow-setTransientParent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setVisibility
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow.Visibility`
        :description: QtGui/QWindow-setVisibility-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setVisible
        :args:
            bool
        :description: QtGui/QWindow-setVisible-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setWidth
        :args:
            int
        :description: QtGui/QWindow-setWidth-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setWindowState
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowState`
        :description: QtGui/QWindow-setWindowState-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setWindowStates
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowStates`, :sip:ref:`~PyQt5.QtCore.Qt.WindowState`]
        :description: QtGui/QWindow-setWindowStates-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setX
        :args:
            int
        :description: QtGui/QWindow-setX-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.setY
        :args:
            int
        :description: QtGui/QWindow-setY-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.show
        :description: QtGui/QWindow-show-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtGui/QWindow-showEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.showFullScreen
        :description: QtGui/QWindow-showFullScreen-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.showMaximized
        :description: QtGui/QWindow-showMaximized-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.showMinimized
        :description: QtGui/QWindow-showMinimized-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.showNormal
        :description: QtGui/QWindow-showNormal-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.size
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-size-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.sizeIncrement
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QWindow-sizeIncrement-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.surfaceType
        :returns:
            :sip:ref:`~PyQt5.QtGui.QSurface.SurfaceType`
        :description: QtGui/QWindow-surfaceType-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.tabletEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QTabletEvent`
        :description: QtGui/QWindow-tabletEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.title
        :returns:
            str
        :description: QtGui/QWindow-title-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.touchEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QTouchEvent`
        :description: QtGui/QWindow-touchEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.transientParent
        :returns:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtGui/QWindow-transientParent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.type
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowType`
        :description: QtGui/QWindow-type-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.unsetCursor
        :description: QtGui/QWindow-unsetCursor-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.visibility
        :returns:
            :sip:ref:`~PyQt5.QtGui.QWindow.Visibility`
        :description: QtGui/QWindow-visibility-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.wheelEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWheelEvent`
        :description: QtGui/QWindow-wheelEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.width
        :returns:
            int
        :description: QtGui/QWindow-width-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.windowState
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowState`
        :description: QtGui/QWindow-windowState-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.windowStates
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowStates`
        :description: QtGui/QWindow-windowStates-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.winId
        :returns:
            sip.voidptr
        :description: QtGui/QWindow-winId-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.x
        :returns:
            int
        :description: QtGui/QWindow-x-f.rst

    .. sip:method:: PyQt5.QtGui.QWindow.y
        :returns:
            int
        :description: QtGui/QWindow-y-f.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.activeChanged
        :description: QtGui/QWindow-activeChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.contentOrientationChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QWindow-contentOrientationChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.focusObjectChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtGui/QWindow-focusObjectChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.heightChanged
        :args:
            int
        :description: QtGui/QWindow-heightChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.maximumHeightChanged
        :args:
            int
        :description: QtGui/QWindow-maximumHeightChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.maximumWidthChanged
        :args:
            int
        :description: QtGui/QWindow-maximumWidthChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.minimumHeightChanged
        :args:
            int
        :description: QtGui/QWindow-minimumHeightChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.minimumWidthChanged
        :args:
            int
        :description: QtGui/QWindow-minimumWidthChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.modalityChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowModality`
        :description: QtGui/QWindow-modalityChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.opacityChanged
        :args:
            float
        :description: QtGui/QWindow-opacityChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.screenChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QScreen`
        :description: QtGui/QWindow-screenChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.visibilityChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow.Visibility`
        :description: QtGui/QWindow-visibilityChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.visibleChanged
        :args:
            bool
        :description: QtGui/QWindow-visibleChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.widthChanged
        :args:
            int
        :description: QtGui/QWindow-widthChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.windowStateChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.WindowState`
        :description: QtGui/QWindow-windowStateChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.windowTitleChanged
        :args:
            str
        :description: QtGui/QWindow-windowTitleChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.xChanged
        :args:
            int
        :description: QtGui/QWindow-xChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QWindow.yChanged
        :args:
            int
        :description: QtGui/QWindow-yChanged-s.rst
