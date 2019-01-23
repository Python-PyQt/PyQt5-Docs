:orphan:

.. sip:class:: PyQt5.QtWinExtras.QtWin
    :description: QtWinExtras/QtWin-c.rst

    .. sip:enum:: PyQt5.QtWinExtras.QtWin.HBitmapFormat
        :description: QtWinExtras/QtWin-HBitmapFormat-e.rst

        .. sip:enum-member:: PyQt5.QtWinExtras.QtWin.HBitmapFormat.HBitmapAlpha
            :description: QtWinExtras/QtWin-HBitmapFormat-HBitmapAlpha-v.rst

        .. sip:enum-member:: PyQt5.QtWinExtras.QtWin.HBitmapFormat.HBitmapNoAlpha
            :description: QtWinExtras/QtWin-HBitmapFormat-HBitmapNoAlpha-v.rst

        .. sip:enum-member:: PyQt5.QtWinExtras.QtWin.HBitmapFormat.HBitmapPremultipliedAlpha
            :description: QtWinExtras/QtWin-HBitmapFormat-HBitmapPremultipliedAlpha-v.rst

    .. sip:enum:: PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy
        :description: QtWinExtras/QtWin-WindowFlip3DPolicy-e.rst

        .. sip:enum-member:: PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy.FlipDefault
            :description: QtWinExtras/QtWin-WindowFlip3DPolicy-FlipDefault-v.rst

        .. sip:enum-member:: PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy.FlipExcludeAbove
            :description: QtWinExtras/QtWin-WindowFlip3DPolicy-FlipExcludeAbove-v.rst

        .. sip:enum-member:: PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy.FlipExcludeBelow
            :description: QtWinExtras/QtWin-WindowFlip3DPolicy-FlipExcludeBelow-v.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.colorizationColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
            bool
        :static:
        :description: QtWinExtras/QtWin-colorizationColor-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.createMask
        :args:
            :sip:ref:`~PyQt5.QtGui.QBitmap`
        :returns:
            sip.voidptr
        :static:
        :description: QtWinExtras/QtWin-createMask-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.disableBlurBehindWindow
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtWinExtras/QtWin-disableBlurBehindWindow-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.disableBlurBehindWindow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :static:
        :description: QtWinExtras/QtWin-disableBlurBehindWindow-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.enableBlurBehindWindow
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtWinExtras/QtWin-enableBlurBehindWindow-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.enableBlurBehindWindow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :static:
        :description: QtWinExtras/QtWin-enableBlurBehindWindow-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.enableBlurBehindWindow
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            :sip:ref:`~PyQt5.QtGui.QRegion`
        :static:
        :description: QtWinExtras/QtWin-enableBlurBehindWindow-f-2.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.enableBlurBehindWindow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            :sip:ref:`~PyQt5.QtGui.QRegion`
        :static:
        :description: QtWinExtras/QtWin-enableBlurBehindWindow-f-3.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.errorStringFromHresult
        :args:
            int
        :returns:
            str
        :static:
        :description: QtWinExtras/QtWin-errorStringFromHresult-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.extendFrameIntoClientArea
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            :sip:ref:`~PyQt5.QtCore.QMargins`
        :static:
        :description: QtWinExtras/QtWin-extendFrameIntoClientArea-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.extendFrameIntoClientArea
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            :sip:ref:`~PyQt5.QtCore.QMargins`
        :static:
        :description: QtWinExtras/QtWin-extendFrameIntoClientArea-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.extendFrameIntoClientArea
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            int
            int
            int
            int
        :static:
        :description: QtWinExtras/QtWin-extendFrameIntoClientArea-f-2.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.extendFrameIntoClientArea
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            int
            int
            int
            int
        :static:
        :description: QtWinExtras/QtWin-extendFrameIntoClientArea-f-3.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.fromHBITMAP
        :args:
            sip.voidptr
            format: :sip:ref:`~PyQt5.QtWinExtras.QtWin.HBitmapFormat` = :sip:ref:`~PyQt5.QtWinExtras.QtWin.HBitmapFormat.HBitmapNoAlpha`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :static:
        :description: QtWinExtras/QtWin-fromHBITMAP-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.fromHICON
        :args:
            sip.voidptr
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :static:
        :description: QtWinExtras/QtWin-fromHICON-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.fromHRGN
        :args:
            sip.voidptr
        :returns:
            :sip:ref:`~PyQt5.QtGui.QRegion`
        :static:
        :description: QtWinExtras/QtWin-fromHRGN-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.imageFromHBITMAP
        :args:
            sip.voidptr
            sip.voidptr
            int
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :static:
        :description: QtWinExtras/QtWin-imageFromHBITMAP-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.isCompositionEnabled
        :returns:
            bool
        :static:
        :description: QtWinExtras/QtWin-isCompositionEnabled-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.isCompositionOpaque
        :returns:
            bool
        :static:
        :description: QtWinExtras/QtWin-isCompositionOpaque-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.isWindowExcludedFromPeek
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :returns:
            bool
        :static:
        :description: QtWinExtras/QtWin-isWindowExcludedFromPeek-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.isWindowExcludedFromPeek
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :returns:
            bool
        :static:
        :description: QtWinExtras/QtWin-isWindowExcludedFromPeek-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.isWindowPeekDisallowed
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :returns:
            bool
        :static:
        :description: QtWinExtras/QtWin-isWindowPeekDisallowed-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.isWindowPeekDisallowed
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :returns:
            bool
        :static:
        :description: QtWinExtras/QtWin-isWindowPeekDisallowed-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.markFullscreenWindow
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            fullscreen: bool = True
        :static:
        :description: QtWinExtras/QtWin-markFullscreenWindow-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.markFullscreenWindow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            fullscreen: bool = True
        :static:
        :description: QtWinExtras/QtWin-markFullscreenWindow-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.realColorizationColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :static:
        :description: QtWinExtras/QtWin-realColorizationColor-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.resetExtendedFrame
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtWinExtras/QtWin-resetExtendedFrame-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.resetExtendedFrame
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :static:
        :description: QtWinExtras/QtWin-resetExtendedFrame-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setCompositionEnabled
        :args:
            bool
        :static:
        :description: QtWinExtras/QtWin-setCompositionEnabled-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setCurrentProcessExplicitAppUserModelID
        :args:
            str
        :static:
        :description: QtWinExtras/QtWin-setCurrentProcessExplicitAppUserModelID-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setWindowDisallowPeek
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            bool
        :static:
        :description: QtWinExtras/QtWin-setWindowDisallowPeek-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setWindowDisallowPeek
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            bool
        :static:
        :description: QtWinExtras/QtWin-setWindowDisallowPeek-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setWindowExcludedFromPeek
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            bool
        :static:
        :description: QtWinExtras/QtWin-setWindowExcludedFromPeek-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setWindowExcludedFromPeek
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            bool
        :static:
        :description: QtWinExtras/QtWin-setWindowExcludedFromPeek-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setWindowFlip3DPolicy
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
            :sip:ref:`~PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy`
        :static:
        :description: QtWinExtras/QtWin-setWindowFlip3DPolicy-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.setWindowFlip3DPolicy
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            :sip:ref:`~PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy`
        :static:
        :description: QtWinExtras/QtWin-setWindowFlip3DPolicy-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.stringFromHresult
        :args:
            int
        :returns:
            str
        :static:
        :description: QtWinExtras/QtWin-stringFromHresult-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarActivateTab
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtWinExtras/QtWin-taskbarActivateTab-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarActivateTab
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :static:
        :description: QtWinExtras/QtWin-taskbarActivateTab-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarActivateTabAlt
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtWinExtras/QtWin-taskbarActivateTabAlt-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarActivateTabAlt
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :static:
        :description: QtWinExtras/QtWin-taskbarActivateTabAlt-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarAddTab
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtWinExtras/QtWin-taskbarAddTab-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarAddTab
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :static:
        :description: QtWinExtras/QtWin-taskbarAddTab-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarDeleteTab
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :static:
        :description: QtWinExtras/QtWin-taskbarDeleteTab-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.taskbarDeleteTab
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :static:
        :description: QtWinExtras/QtWin-taskbarDeleteTab-f-1.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.toHBITMAP
        :args:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            format: :sip:ref:`~PyQt5.QtWinExtras.QtWin.HBitmapFormat` = :sip:ref:`~PyQt5.QtWinExtras.QtWin.HBitmapFormat.HBitmapNoAlpha`
        :returns:
            sip.voidptr
        :static:
        :description: QtWinExtras/QtWin-toHBITMAP-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.toHICON
        :args:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :returns:
            sip.voidptr
        :static:
        :description: QtWinExtras/QtWin-toHICON-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.toHRGN
        :args:
            :sip:ref:`~PyQt5.QtGui.QRegion`
        :returns:
            sip.voidptr
        :static:
        :description: QtWinExtras/QtWin-toHRGN-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.windowFlip3DPolicy
        :args:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :returns:
            :sip:ref:`~PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy`
        :static:
        :description: QtWinExtras/QtWin-windowFlip3DPolicy-f.rst

    .. sip:method:: PyQt5.QtWinExtras.QtWin.windowFlip3DPolicy
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :returns:
            :sip:ref:`~PyQt5.QtWinExtras.QtWin.WindowFlip3DPolicy`
        :static:
        :description: QtWinExtras/QtWin-windowFlip3DPolicy-f-1.rst
