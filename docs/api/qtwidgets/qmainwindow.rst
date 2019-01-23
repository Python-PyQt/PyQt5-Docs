:orphan:

.. sip:class:: PyQt5.QtWidgets.QMainWindow
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QMainWindow-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QMainWindow.DockOption
        :description: QtWidgets/QMainWindow-DockOption-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMainWindow.DockOption.AllowNestedDocks
            :description: QtWidgets/QMainWindow-DockOption-AllowNestedDocks-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMainWindow.DockOption.AllowTabbedDocks
            :description: QtWidgets/QMainWindow-DockOption-AllowTabbedDocks-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMainWindow.DockOption.AnimatedDocks
            :description: QtWidgets/QMainWindow-DockOption-AnimatedDocks-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMainWindow.DockOption.ForceTabbedDocks
            :description: QtWidgets/QMainWindow-DockOption-ForceTabbedDocks-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMainWindow.DockOption.GroupedDragging
            :description: QtWidgets/QMainWindow-DockOption-GroupedDragging-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMainWindow.DockOption.VerticalTabs
            :description: QtWidgets/QMainWindow-DockOption-VerticalTabs-v.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QMainWindow-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.addDockWidget
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
        :description: QtWidgets/QMainWindow-addDockWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.addDockWidget
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
        :description: QtWidgets/QMainWindow-addDockWidget-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.addToolBar
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :description: QtWidgets/QMainWindow-addToolBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.addToolBar
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :description: QtWidgets/QMainWindow-addToolBar-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.addToolBar
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ToolBarArea`
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :description: QtWidgets/QMainWindow-addToolBar-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.addToolBarBreak
        :args:
            area: :sip:ref:`~PyQt5.QtCore.Qt.ToolBarArea` = :sip:ref:`~PyQt5.QtCore.Qt.ToolBarArea.TopToolBarArea`
        :description: QtWidgets/QMainWindow-addToolBarBreak-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.centralWidget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMainWindow-centralWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.contextMenuEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QContextMenuEvent`
        :description: QtWidgets/QMainWindow-contextMenuEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.corner
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.Corner`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
        :description: QtWidgets/QMainWindow-corner-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.createPopupMenu
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QMainWindow-createPopupMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.dockOptions
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMainWindow.DockOptions`
        :description: QtWidgets/QMainWindow-dockOptions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.dockWidgetArea
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
        :description: QtWidgets/QMainWindow-dockWidgetArea-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.documentMode
        :returns:
            bool
        :description: QtWidgets/QMainWindow-documentMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMainWindow-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.iconSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMainWindow-iconSize-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.insertToolBar
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :description: QtWidgets/QMainWindow-insertToolBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.insertToolBarBreak
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :description: QtWidgets/QMainWindow-insertToolBarBreak-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.isAnimated
        :returns:
            bool
        :description: QtWidgets/QMainWindow-isAnimated-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.isDockNestingEnabled
        :returns:
            bool
        :description: QtWidgets/QMainWindow-isDockNestingEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.isSeparator
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            bool
        :description: QtWidgets/QMainWindow-isSeparator-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.menuBar
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenuBar`
        :description: QtWidgets/QMainWindow-menuBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.menuWidget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMainWindow-menuWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.removeDockWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
        :description: QtWidgets/QMainWindow-removeDockWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.removeToolBar
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :description: QtWidgets/QMainWindow-removeToolBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.removeToolBarBreak
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :description: QtWidgets/QMainWindow-removeToolBarBreak-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.resizeDocks
        :args:
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QDockWidget`]
            Iterable[int]
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
        :description: QtWidgets/QMainWindow-resizeDocks-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.restoreDockWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
        :returns:
            bool
        :description: QtWidgets/QMainWindow-restoreDockWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.restoreState
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            version: int = 0
        :returns:
            bool
        :description: QtWidgets/QMainWindow-restoreState-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.saveState
        :args:
            version: int = 0
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtWidgets/QMainWindow-saveState-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setAnimated
        :args:
            bool
        :description: QtWidgets/QMainWindow-setAnimated-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setCentralWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMainWindow-setCentralWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setCorner
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.Corner`
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
        :description: QtWidgets/QMainWindow-setCorner-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setDockNestingEnabled
        :args:
            bool
        :description: QtWidgets/QMainWindow-setDockNestingEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setDockOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QMainWindow.DockOptions`, :sip:ref:`~PyQt5.QtWidgets.QMainWindow.DockOption`]
        :description: QtWidgets/QMainWindow-setDockOptions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setDocumentMode
        :args:
            bool
        :description: QtWidgets/QMainWindow-setDocumentMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setIconSize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMainWindow-setIconSize-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setMenuBar
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMenuBar`
        :description: QtWidgets/QMainWindow-setMenuBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setMenuWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMainWindow-setMenuWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setStatusBar
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStatusBar`
        :description: QtWidgets/QMainWindow-setStatusBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setTabPosition
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.DockWidgetAreas`, :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`]
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabPosition`
        :description: QtWidgets/QMainWindow-setTabPosition-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setTabShape
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabShape`
        :description: QtWidgets/QMainWindow-setTabShape-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setToolButtonStyle
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ToolButtonStyle`
        :description: QtWidgets/QMainWindow-setToolButtonStyle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.setUnifiedTitleAndToolBarOnMac
        :args:
            bool
        :description: QtWidgets/QMainWindow-setUnifiedTitleAndToolBarOnMac-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.splitDockWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
        :description: QtWidgets/QMainWindow-splitDockWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.statusBar
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QStatusBar`
        :description: QtWidgets/QMainWindow-statusBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.tabifiedDockWidgets
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QDockWidget`]
        :description: QtWidgets/QMainWindow-tabifiedDockWidgets-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.tabifyDockWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
        :description: QtWidgets/QMainWindow-tabifyDockWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.tabPosition
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabPosition`
        :description: QtWidgets/QMainWindow-tabPosition-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.tabShape
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabShape`
        :description: QtWidgets/QMainWindow-tabShape-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.takeCentralWidget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMainWindow-takeCentralWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.toolBarArea
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ToolBarArea`
        :description: QtWidgets/QMainWindow-toolBarArea-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.toolBarBreak
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QToolBar`
        :returns:
            bool
        :description: QtWidgets/QMainWindow-toolBarBreak-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.toolButtonStyle
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ToolButtonStyle`
        :description: QtWidgets/QMainWindow-toolButtonStyle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMainWindow.unifiedTitleAndToolBarOnMac
        :returns:
            bool
        :description: QtWidgets/QMainWindow-unifiedTitleAndToolBarOnMac-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QMainWindow.iconSizeChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMainWindow-iconSizeChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QMainWindow.tabifiedDockWidgetActivated
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget`
        :description: QtWidgets/QMainWindow-tabifiedDockWidgetActivated-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QMainWindow.toolButtonStyleChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ToolButtonStyle`
        :description: QtWidgets/QMainWindow-toolButtonStyleChanged-s.rst
