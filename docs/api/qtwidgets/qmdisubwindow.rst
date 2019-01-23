:orphan:

.. sip:class:: PyQt5.QtWidgets.QMdiSubWindow
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QMdiSubWindow-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QMdiSubWindow.SubWindowOption
        :description: QtWidgets/QMdiSubWindow-SubWindowOption-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiSubWindow.SubWindowOption.RubberBandMove
            :description: QtWidgets/QMdiSubWindow-SubWindowOption-RubberBandMove-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiSubWindow.SubWindowOption.RubberBandResize
            :description: QtWidgets/QMdiSubWindow-SubWindowOption-RubberBandResize-v.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QMdiSubWindow-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.changeEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QMdiSubWindow-changeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.childEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QChildEvent`
        :description: QtWidgets/QMdiSubWindow-childEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.closeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QCloseEvent`
        :description: QtWidgets/QMdiSubWindow-closeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.contextMenuEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QContextMenuEvent`
        :description: QtWidgets/QMdiSubWindow-contextMenuEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMdiSubWindow-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMdiSubWindow-eventFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.focusInEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtWidgets/QMdiSubWindow-focusInEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.focusOutEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtWidgets/QMdiSubWindow-focusOutEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.hideEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QHideEvent`
        :description: QtWidgets/QMdiSubWindow-hideEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.isShaded
        :returns:
            bool
        :description: QtWidgets/QMdiSubWindow-isShaded-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.keyboardPageStep
        :returns:
            int
        :description: QtWidgets/QMdiSubWindow-keyboardPageStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.keyboardSingleStep
        :returns:
            int
        :description: QtWidgets/QMdiSubWindow-keyboardSingleStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QMdiSubWindow-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.leaveEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QMdiSubWindow-leaveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.mdiArea
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMdiArea`
        :description: QtWidgets/QMdiSubWindow-mdiArea-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.minimumSizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMdiSubWindow-minimumSizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.mouseDoubleClickEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMdiSubWindow-mouseDoubleClickEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMdiSubWindow-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMdiSubWindow-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMdiSubWindow-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.moveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMoveEvent`
        :description: QtWidgets/QMdiSubWindow-moveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QMdiSubWindow-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtWidgets/QMdiSubWindow-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.setKeyboardPageStep
        :args:
            int
        :description: QtWidgets/QMdiSubWindow-setKeyboardPageStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.setKeyboardSingleStep
        :args:
            int
        :description: QtWidgets/QMdiSubWindow-setKeyboardSingleStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.setOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow.SubWindowOption`
            on: bool = True
        :description: QtWidgets/QMdiSubWindow-setOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.setSystemMenu
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QMdiSubWindow-setSystemMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.setWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMdiSubWindow-setWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtWidgets/QMdiSubWindow-showEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.showShaded
        :description: QtWidgets/QMdiSubWindow-showShaded-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.showSystemMenu
        :description: QtWidgets/QMdiSubWindow-showSystemMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMdiSubWindow-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.systemMenu
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QMdiSubWindow-systemMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.testOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow.SubWindowOption`
        :returns:
            bool
        :description: QtWidgets/QMdiSubWindow-testOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtWidgets/QMdiSubWindow-timerEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiSubWindow.widget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMdiSubWindow-widget-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QMdiSubWindow.aboutToActivate
        :description: QtWidgets/QMdiSubWindow-aboutToActivate-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QMdiSubWindow.windowStateChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowStates`, :sip:ref:`~PyQt5.QtCore.Qt.WindowState`]
            Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowStates`, :sip:ref:`~PyQt5.QtCore.Qt.WindowState`]
        :description: QtWidgets/QMdiSubWindow-windowStateChanged-s.rst
