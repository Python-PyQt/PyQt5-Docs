:orphan:

.. sip:class:: PyQt5.QtWidgets.QTreeWidget
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QTreeView`
    :description: QtWidgets/QTreeWidget-c.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QTreeWidget-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.addTopLevelItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-addTopLevelItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.addTopLevelItems
        :args:
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`]
        :description: QtWidgets/QTreeWidget-addTopLevelItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.clear
        :description: QtWidgets/QTreeWidget-clear-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.closePersistentEditor
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            column: int = 0
        :description: QtWidgets/QTreeWidget-closePersistentEditor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.collapseItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-collapseItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.columnCount
        :returns:
            int
        :description: QtWidgets/QTreeWidget-columnCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.currentColumn
        :returns:
            int
        :description: QtWidgets/QTreeWidget-currentColumn-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.currentItem
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-currentItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.dropEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDropEvent`
        :description: QtWidgets/QTreeWidget-dropEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.dropMimeData
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
        :returns:
            bool
        :description: QtWidgets/QTreeWidget-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.editItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            column: int = 0
        :description: QtWidgets/QTreeWidget-editItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QTreeWidget-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.expandItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-expandItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.findItems
        :args:
            str
            Union[:sip:ref:`~PyQt5.QtCore.Qt.MatchFlags`, :sip:ref:`~PyQt5.QtCore.Qt.MatchFlag`]
            column: int = 0
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`]
        :description: QtWidgets/QTreeWidget-findItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.headerItem
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-headerItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.indexFromItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            column: int = 0
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QTreeWidget-indexFromItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.indexOfTopLevelItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :returns:
            int
        :description: QtWidgets/QTreeWidget-indexOfTopLevelItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.insertTopLevelItem
        :args:
            int
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-insertTopLevelItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.insertTopLevelItems
        :args:
            int
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`]
        :description: QtWidgets/QTreeWidget-insertTopLevelItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.invisibleRootItem
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-invisibleRootItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.isFirstItemColumnSpanned
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :returns:
            bool
        :description: QtWidgets/QTreeWidget-isFirstItemColumnSpanned-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.isPersistentEditorOpen
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            column: int = 0
        :returns:
            bool
        :description: QtWidgets/QTreeWidget-isPersistentEditorOpen-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.itemAbove
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-itemAbove-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.itemAt
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-itemAt-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.itemAt
        :args:
            int
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-itemAt-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.itemBelow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-itemBelow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.itemFromIndex
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-itemFromIndex-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.itemWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QTreeWidget-itemWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.mimeData
        :args:
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :description: QtWidgets/QTreeWidget-mimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.mimeTypes
        :returns:
            List[str]
        :description: QtWidgets/QTreeWidget-mimeTypes-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.openPersistentEditor
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            column: int = 0
        :description: QtWidgets/QTreeWidget-openPersistentEditor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.removeItemWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-removeItemWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.scrollToItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            hint: :sip:ref:`~PyQt5.QtWidgets.QAbstractItemView.ScrollHint` = :sip:ref:`~PyQt5.QtWidgets.QAbstractItemView.ScrollHint.EnsureVisible`
        :description: QtWidgets/QTreeWidget-scrollToItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.selectedItems
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`]
        :description: QtWidgets/QTreeWidget-selectedItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setColumnCount
        :args:
            int
        :description: QtWidgets/QTreeWidget-setColumnCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setCurrentItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-setCurrentItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setCurrentItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-setCurrentItem-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setCurrentItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
            Union[:sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlags`, :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlag`]
        :description: QtWidgets/QTreeWidget-setCurrentItem-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setFirstItemColumnSpanned
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            bool
        :description: QtWidgets/QTreeWidget-setFirstItemColumnSpanned-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setHeaderItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-setHeaderItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setHeaderLabel
        :args:
            str
        :description: QtWidgets/QTreeWidget-setHeaderLabel-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setHeaderLabels
        :args:
            Iterable[str]
        :description: QtWidgets/QTreeWidget-setHeaderLabels-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setItemWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QTreeWidget-setItemWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.setSelectionModel
        :args:
            :sip:ref:`~PyQt5.QtCore.QItemSelectionModel`
        :description: QtWidgets/QTreeWidget-setSelectionModel-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.sortColumn
        :returns:
            int
        :description: QtWidgets/QTreeWidget-sortColumn-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.sortItems
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.SortOrder`
        :description: QtWidgets/QTreeWidget-sortItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.supportedDropActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtWidgets/QTreeWidget-supportedDropActions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.takeTopLevelItem
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-takeTopLevelItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.topLevelItem
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-topLevelItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.topLevelItemCount
        :returns:
            int
        :description: QtWidgets/QTreeWidget-topLevelItemCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QTreeWidget.visualItemRect
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QTreeWidget-visualItemRect-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.currentItemChanged
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-currentItemChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemActivated
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-itemActivated-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemChanged
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-itemChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemClicked
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-itemClicked-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemCollapsed
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-itemCollapsed-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemDoubleClicked
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-itemDoubleClicked-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemEntered
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-itemEntered-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemExpanded
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
        :description: QtWidgets/QTreeWidget-itemExpanded-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemPressed
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QTreeWidgetItem`
            int
        :description: QtWidgets/QTreeWidget-itemPressed-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QTreeWidget.itemSelectionChanged
        :description: QtWidgets/QTreeWidget-itemSelectionChanged-s.rst
