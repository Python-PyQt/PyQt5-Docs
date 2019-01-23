:orphan:

.. sip:class:: PyQt5.QtWidgets.QMenu
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QMenu-c.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QMenu-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.__init__
        :args:
            str
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QMenu-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.actionAt
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-actionAt-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.actionEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QActionEvent`
        :description: QtWidgets/QMenu-actionEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.actionGeometry
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QMenu-actionGeometry-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.activeAction
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-activeAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addAction
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addAction
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addAction-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addAction
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addAction-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addAction
        :args:
            str
            PYQT_SLOT
            shortcut: Union[:sip:ref:`~PyQt5.QtGui.QKeySequence`, :sip:ref:`~PyQt5.QtGui.QKeySequence.StandardKey`, str, int] = 0
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addAction-f-3.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addAction
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
            str
            PYQT_SLOT
            shortcut: Union[:sip:ref:`~PyQt5.QtGui.QKeySequence`, :sip:ref:`~PyQt5.QtGui.QKeySequence.StandardKey`, str, int] = 0
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addAction-f-4.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addMenu
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addMenu
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QMenu-addMenu-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addMenu
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QMenu-addMenu-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addSection
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addSection-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addSection
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addSection-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.addSeparator
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-addSeparator-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.changeEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QMenu-changeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.clear
        :description: QtWidgets/QMenu-clear-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.columnCount
        :returns:
            int
        :description: QtWidgets/QMenu-columnCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.defaultAction
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-defaultAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.enterEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QMenu-enterEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMenu-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.exec
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-exec-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.exec
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
            action: :sip:ref:`~PyQt5.QtWidgets.QAction` = None
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-exec-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.exec
        :args:
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QAction`]
            :sip:ref:`~PyQt5.QtCore.QPoint`
            at: :sip:ref:`~PyQt5.QtWidgets.QAction` = None
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :static:
        :description: QtWidgets/QMenu-exec-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.exec_
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-exec_-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.exec_
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
            action: :sip:ref:`~PyQt5.QtWidgets.QAction` = None
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-exec_-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.exec_
        :args:
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QAction`]
            :sip:ref:`~PyQt5.QtCore.QPoint`
            at: :sip:ref:`~PyQt5.QtWidgets.QAction` = None
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :static:
        :description: QtWidgets/QMenu-exec_-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.focusNextPrevChild
        :args:
            bool
        :returns:
            bool
        :description: QtWidgets/QMenu-focusNextPrevChild-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.hideEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QHideEvent`
        :description: QtWidgets/QMenu-hideEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.hideTearOffMenu
        :description: QtWidgets/QMenu-hideTearOffMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.icon
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QMenu-icon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.initStyleOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionMenuItem`
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-initStyleOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.insertMenu
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-insertMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.insertSection
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-insertSection-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.insertSection
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
            :sip:ref:`~PyQt5.QtGui.QIcon`
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-insertSection-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.insertSeparator
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-insertSeparator-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.isEmpty
        :returns:
            bool
        :description: QtWidgets/QMenu-isEmpty-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.isTearOffEnabled
        :returns:
            bool
        :description: QtWidgets/QMenu-isTearOffEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.isTearOffMenuVisible
        :returns:
            bool
        :description: QtWidgets/QMenu-isTearOffMenuVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QMenu-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.leaveEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QMenu-leaveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.menuAction
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-menuAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMenu-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMenu-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMenu-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QMenu-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.popup
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
            action: :sip:ref:`~PyQt5.QtWidgets.QAction` = None
        :description: QtWidgets/QMenu-popup-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.separatorsCollapsible
        :returns:
            bool
        :description: QtWidgets/QMenu-separatorsCollapsible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setActiveAction
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-setActiveAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setAsDockMenu
        :description: QtWidgets/QMenu-setAsDockMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setDefaultAction
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-setDefaultAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setIcon
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QMenu-setIcon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setNoReplayFor
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMenu-setNoReplayFor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setSeparatorsCollapsible
        :args:
            bool
        :description: QtWidgets/QMenu-setSeparatorsCollapsible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setTearOffEnabled
        :args:
            bool
        :description: QtWidgets/QMenu-setTearOffEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setTitle
        :args:
            str
        :description: QtWidgets/QMenu-setTitle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.setToolTipsVisible
        :args:
            bool
        :description: QtWidgets/QMenu-setToolTipsVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.showTearOffMenu
        :description: QtWidgets/QMenu-showTearOffMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.showTearOffMenu
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtWidgets/QMenu-showTearOffMenu-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMenu-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtWidgets/QMenu-timerEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.title
        :returns:
            str
        :description: QtWidgets/QMenu-title-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.toolTipsVisible
        :returns:
            bool
        :description: QtWidgets/QMenu-toolTipsVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenu.wheelEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWheelEvent`
        :description: QtWidgets/QMenu-wheelEvent-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QMenu.aboutToHide
        :description: QtWidgets/QMenu-aboutToHide-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QMenu.aboutToShow
        :description: QtWidgets/QMenu-aboutToShow-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QMenu.hovered
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-hovered-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QMenu.triggered
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenu-triggered-s.rst
