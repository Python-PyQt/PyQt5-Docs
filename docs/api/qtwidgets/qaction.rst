:orphan:

.. sip:class:: PyQt5.QtWidgets.QAction
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWidgets/QAction-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QAction.ActionEvent
        :description: QtWidgets/QAction-ActionEvent-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.ActionEvent.Hover
            :description: QtWidgets/QAction-ActionEvent-Hover-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.ActionEvent.Trigger
            :description: QtWidgets/QAction-ActionEvent-Trigger-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QAction.MenuRole
        :description: QtWidgets/QAction-MenuRole-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.MenuRole.AboutQtRole
            :description: QtWidgets/QAction-MenuRole-AboutQtRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.MenuRole.AboutRole
            :description: QtWidgets/QAction-MenuRole-AboutRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.MenuRole.ApplicationSpecificRole
            :description: QtWidgets/QAction-MenuRole-ApplicationSpecificRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.MenuRole.NoRole
            :description: QtWidgets/QAction-MenuRole-NoRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.MenuRole.PreferencesRole
            :description: QtWidgets/QAction-MenuRole-PreferencesRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.MenuRole.QuitRole
            :description: QtWidgets/QAction-MenuRole-QuitRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.MenuRole.TextHeuristicRole
            :description: QtWidgets/QAction-MenuRole-TextHeuristicRole-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QAction.Priority
        :description: QtWidgets/QAction-Priority-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.Priority.HighPriority
            :description: QtWidgets/QAction-Priority-HighPriority-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.Priority.LowPriority
            :description: QtWidgets/QAction-Priority-LowPriority-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAction.Priority.NormalPriority
            :description: QtWidgets/QAction-Priority-NormalPriority-v.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QAction-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.__init__
        :args:
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QAction-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QAction-__init__-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.actionGroup
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QActionGroup`
        :description: QtWidgets/QAction-actionGroup-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.activate
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction.ActionEvent`
        :description: QtWidgets/QAction-activate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.associatedGraphicsWidgets
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsWidget`]
        :description: QtWidgets/QAction-associatedGraphicsWidgets-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.associatedWidgets
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QWidget`]
        :description: QtWidgets/QAction-associatedWidgets-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.autoRepeat
        :returns:
            bool
        :description: QtWidgets/QAction-autoRepeat-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.data
        :returns:
            Any
        :description: QtWidgets/QAction-data-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QAction-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.font
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QAction-font-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.hover
        :description: QtWidgets/QAction-hover-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.icon
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QAction-icon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.iconText
        :returns:
            str
        :description: QtWidgets/QAction-iconText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.isCheckable
        :returns:
            bool
        :description: QtWidgets/QAction-isCheckable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.isChecked
        :returns:
            bool
        :description: QtWidgets/QAction-isChecked-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.isEnabled
        :returns:
            bool
        :description: QtWidgets/QAction-isEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.isIconVisibleInMenu
        :returns:
            bool
        :description: QtWidgets/QAction-isIconVisibleInMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.isSeparator
        :returns:
            bool
        :description: QtWidgets/QAction-isSeparator-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.isShortcutVisibleInContextMenu
        :returns:
            bool
        :description: QtWidgets/QAction-isShortcutVisibleInContextMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.isVisible
        :returns:
            bool
        :description: QtWidgets/QAction-isVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.menu
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QAction-menu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.menuRole
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction.MenuRole`
        :description: QtWidgets/QAction-menuRole-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.parentWidget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QAction-parentWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.priority
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction.Priority`
        :description: QtWidgets/QAction-priority-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setActionGroup
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QActionGroup`
        :description: QtWidgets/QAction-setActionGroup-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setAutoRepeat
        :args:
            bool
        :description: QtWidgets/QAction-setAutoRepeat-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setCheckable
        :args:
            bool
        :description: QtWidgets/QAction-setCheckable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setChecked
        :args:
            bool
        :description: QtWidgets/QAction-setChecked-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setData
        :args:
            Any
        :description: QtWidgets/QAction-setData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setDisabled
        :args:
            bool
        :description: QtWidgets/QAction-setDisabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setEnabled
        :args:
            bool
        :description: QtWidgets/QAction-setEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setFont
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QAction-setFont-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setIcon
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QAction-setIcon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setIconText
        :args:
            str
        :description: QtWidgets/QAction-setIconText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setIconVisibleInMenu
        :args:
            bool
        :description: QtWidgets/QAction-setIconVisibleInMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setMenu
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QAction-setMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setMenuRole
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction.MenuRole`
        :description: QtWidgets/QAction-setMenuRole-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setPriority
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction.Priority`
        :description: QtWidgets/QAction-setPriority-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setSeparator
        :args:
            bool
        :description: QtWidgets/QAction-setSeparator-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setShortcut
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QKeySequence`, :sip:ref:`~PyQt5.QtGui.QKeySequence.StandardKey`, str, int]
        :description: QtWidgets/QAction-setShortcut-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setShortcutContext
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ShortcutContext`
        :description: QtWidgets/QAction-setShortcutContext-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setShortcuts
        :args:
            Iterable[Union[:sip:ref:`~PyQt5.QtGui.QKeySequence`, :sip:ref:`~PyQt5.QtGui.QKeySequence.StandardKey`, str, int]]
        :description: QtWidgets/QAction-setShortcuts-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setShortcuts
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeySequence.StandardKey`
        :description: QtWidgets/QAction-setShortcuts-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setShortcutVisibleInContextMenu
        :args:
            bool
        :description: QtWidgets/QAction-setShortcutVisibleInContextMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setStatusTip
        :args:
            str
        :description: QtWidgets/QAction-setStatusTip-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setText
        :args:
            str
        :description: QtWidgets/QAction-setText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setToolTip
        :args:
            str
        :description: QtWidgets/QAction-setToolTip-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setVisible
        :args:
            bool
        :description: QtWidgets/QAction-setVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.setWhatsThis
        :args:
            str
        :description: QtWidgets/QAction-setWhatsThis-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.shortcut
        :returns:
            :sip:ref:`~PyQt5.QtGui.QKeySequence`
        :description: QtWidgets/QAction-shortcut-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.shortcutContext
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ShortcutContext`
        :description: QtWidgets/QAction-shortcutContext-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.shortcuts
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QKeySequence`]
        :description: QtWidgets/QAction-shortcuts-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.showStatusText
        :args:
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            bool
        :description: QtWidgets/QAction-showStatusText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.statusTip
        :returns:
            str
        :description: QtWidgets/QAction-statusTip-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.text
        :returns:
            str
        :description: QtWidgets/QAction-text-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.toggle
        :description: QtWidgets/QAction-toggle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.toolTip
        :returns:
            str
        :description: QtWidgets/QAction-toolTip-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.trigger
        :description: QtWidgets/QAction-trigger-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAction.whatsThis
        :returns:
            str
        :description: QtWidgets/QAction-whatsThis-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QAction.changed
        :description: QtWidgets/QAction-changed-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QAction.hovered
        :description: QtWidgets/QAction-hovered-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QAction.toggled
        :args:
            bool
        :description: QtWidgets/QAction-toggled-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QAction.triggered
        :args:
            checked: bool = False
        :description: QtWidgets/QAction-triggered-s.rst
