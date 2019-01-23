:orphan:

.. sip:class:: PyQt5.QtWidgets.QMdiArea
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QAbstractScrollArea`
    :description: QtWidgets/QMdiArea-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QMdiArea.AreaOption
        :description: QtWidgets/QMdiArea-AreaOption-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiArea.AreaOption.DontMaximizeSubWindowOnActivation
            :description: QtWidgets/QMdiArea-AreaOption-DontMaximizeSubWindowOnActivation-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QMdiArea.ViewMode
        :description: QtWidgets/QMdiArea-ViewMode-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiArea.ViewMode.SubWindowView
            :description: QtWidgets/QMdiArea-ViewMode-SubWindowView-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiArea.ViewMode.TabbedView
            :description: QtWidgets/QMdiArea-ViewMode-TabbedView-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QMdiArea.WindowOrder
        :description: QtWidgets/QMdiArea-WindowOrder-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiArea.WindowOrder.ActivationHistoryOrder
            :description: QtWidgets/QMdiArea-WindowOrder-ActivationHistoryOrder-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiArea.WindowOrder.CreationOrder
            :description: QtWidgets/QMdiArea-WindowOrder-CreationOrder-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QMdiArea.WindowOrder.StackingOrder
            :description: QtWidgets/QMdiArea-WindowOrder-StackingOrder-v.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QMdiArea-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.activateNextSubWindow
        :description: QtWidgets/QMdiArea-activateNextSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.activatePreviousSubWindow
        :description: QtWidgets/QMdiArea-activatePreviousSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.activationOrder
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMdiArea.WindowOrder`
        :description: QtWidgets/QMdiArea-activationOrder-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.activeSubWindow
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow`
        :description: QtWidgets/QMdiArea-activeSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.addSubWindow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow`
        :description: QtWidgets/QMdiArea-addSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.background
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtWidgets/QMdiArea-background-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.cascadeSubWindows
        :description: QtWidgets/QMdiArea-cascadeSubWindows-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.childEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QChildEvent`
        :description: QtWidgets/QMdiArea-childEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.closeActiveSubWindow
        :description: QtWidgets/QMdiArea-closeActiveSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.closeAllSubWindows
        :description: QtWidgets/QMdiArea-closeAllSubWindows-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.currentSubWindow
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow`
        :description: QtWidgets/QMdiArea-currentSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.documentMode
        :returns:
            bool
        :description: QtWidgets/QMdiArea-documentMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMdiArea-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMdiArea-eventFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.minimumSizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMdiArea-minimumSizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QMdiArea-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.removeSubWindow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMdiArea-removeSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtWidgets/QMdiArea-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.scrollContentsBy
        :args:
            int
            int
        :description: QtWidgets/QMdiArea-scrollContentsBy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setActivationOrder
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiArea.WindowOrder`
        :description: QtWidgets/QMdiArea-setActivationOrder-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setActiveSubWindow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow`
        :description: QtWidgets/QMdiArea-setActiveSubWindow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setBackground
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtWidgets/QMdiArea-setBackground-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setDocumentMode
        :args:
            bool
        :description: QtWidgets/QMdiArea-setDocumentMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiArea.AreaOption`
            on: bool = True
        :description: QtWidgets/QMdiArea-setOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setTabPosition
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabPosition`
        :description: QtWidgets/QMdiArea-setTabPosition-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setTabsClosable
        :args:
            bool
        :description: QtWidgets/QMdiArea-setTabsClosable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setTabShape
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabShape`
        :description: QtWidgets/QMdiArea-setTabShape-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setTabsMovable
        :args:
            bool
        :description: QtWidgets/QMdiArea-setTabsMovable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setupViewport
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMdiArea-setupViewport-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.setViewMode
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiArea.ViewMode`
        :description: QtWidgets/QMdiArea-setViewMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtWidgets/QMdiArea-showEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMdiArea-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.subWindowList
        :args:
            order: :sip:ref:`~PyQt5.QtWidgets.QMdiArea.WindowOrder` = :sip:ref:`~PyQt5.QtWidgets.QMdiArea.WindowOrder.CreationOrder`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow`]
        :description: QtWidgets/QMdiArea-subWindowList-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.tabPosition
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabPosition`
        :description: QtWidgets/QMdiArea-tabPosition-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.tabsClosable
        :returns:
            bool
        :description: QtWidgets/QMdiArea-tabsClosable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.tabShape
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTabWidget.TabShape`
        :description: QtWidgets/QMdiArea-tabShape-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.tabsMovable
        :returns:
            bool
        :description: QtWidgets/QMdiArea-tabsMovable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.testOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiArea.AreaOption`
        :returns:
            bool
        :description: QtWidgets/QMdiArea-testOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.tileSubWindows
        :description: QtWidgets/QMdiArea-tileSubWindows-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtWidgets/QMdiArea-timerEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.viewMode
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMdiArea.ViewMode`
        :description: QtWidgets/QMdiArea-viewMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMdiArea.viewportEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMdiArea-viewportEvent-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QMdiArea.subWindowActivated
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMdiSubWindow`
        :description: QtWidgets/QMdiArea-subWindowActivated-s.rst
