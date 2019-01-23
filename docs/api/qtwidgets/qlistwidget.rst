:orphan:

.. sip:class:: PyQt5.QtWidgets.QListWidget
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QListView`
    :description: QtWidgets/QListWidget-c.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QListWidget-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.addItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-addItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.addItem
        :args:
            str
        :description: QtWidgets/QListWidget-addItem-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.addItems
        :args:
            Iterable[str]
        :description: QtWidgets/QListWidget-addItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.clear
        :description: QtWidgets/QListWidget-clear-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.closePersistentEditor
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-closePersistentEditor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.count
        :returns:
            int
        :description: QtWidgets/QListWidget-count-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.currentItem
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-currentItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.currentRow
        :returns:
            int
        :description: QtWidgets/QListWidget-currentRow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.dropEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDropEvent`
        :description: QtWidgets/QListWidget-dropEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.dropMimeData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
        :returns:
            bool
        :description: QtWidgets/QListWidget-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.editItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-editItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QListWidget-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.findItems
        :args:
            str
            Union[:sip:ref:`~PyQt5.QtCore.Qt.MatchFlags`, :sip:ref:`~PyQt5.QtCore.Qt.MatchFlag`]
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`]
        :description: QtWidgets/QListWidget-findItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.indexFromItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QListWidget-indexFromItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.insertItem
        :args:
            int
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-insertItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.insertItem
        :args:
            int
            str
        :description: QtWidgets/QListWidget-insertItem-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.insertItems
        :args:
            int
            Iterable[str]
        :description: QtWidgets/QListWidget-insertItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.isPersistentEditorOpen
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :returns:
            bool
        :description: QtWidgets/QListWidget-isPersistentEditorOpen-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.isSortingEnabled
        :returns:
            bool
        :description: QtWidgets/QListWidget-isSortingEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.item
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-item-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.itemAt
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemAt-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.itemAt
        :args:
            int
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemAt-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.itemFromIndex
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemFromIndex-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.items
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`]
        :description: QtWidgets/QListWidget-items-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.itemWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QListWidget-itemWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.__len__
        :returns:
            int
        :description: QtWidgets/QListWidget-__len__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.mimeData
        :args:
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :description: QtWidgets/QListWidget-mimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.mimeTypes
        :returns:
            List[str]
        :description: QtWidgets/QListWidget-mimeTypes-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.openPersistentEditor
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-openPersistentEditor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.removeItemWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-removeItemWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.row
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :returns:
            int
        :description: QtWidgets/QListWidget-row-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.scrollToItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
            hint: :sip:ref:`~PyQt5.QtWidgets.QAbstractItemView.ScrollHint` = :sip:ref:`~PyQt5.QtWidgets.QAbstractItemView.ScrollHint.EnsureVisible`
        :description: QtWidgets/QListWidget-scrollToItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.selectedItems
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`]
        :description: QtWidgets/QListWidget-selectedItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.setCurrentItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-setCurrentItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.setCurrentItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
            Union[:sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlags`, :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlag`]
        :description: QtWidgets/QListWidget-setCurrentItem-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.setCurrentRow
        :args:
            int
        :description: QtWidgets/QListWidget-setCurrentRow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.setCurrentRow
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlags`, :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlag`]
        :description: QtWidgets/QListWidget-setCurrentRow-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.setItemWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QListWidget-setItemWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.setSelectionModel
        :args:
            :sip:ref:`~PyQt5.QtCore.QItemSelectionModel`
        :description: QtWidgets/QListWidget-setSelectionModel-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.setSortingEnabled
        :args:
            bool
        :description: QtWidgets/QListWidget-setSortingEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.sortItems
        :args:
            order: :sip:ref:`~PyQt5.QtCore.Qt.SortOrder` = :sip:ref:`~PyQt5.QtCore.Qt.SortOrder.AscendingOrder`
        :description: QtWidgets/QListWidget-sortItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.supportedDropActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtWidgets/QListWidget-supportedDropActions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.takeItem
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-takeItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QListWidget.visualItemRect
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QListWidget-visualItemRect-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.currentItemChanged
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-currentItemChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.currentRowChanged
        :args:
            int
        :description: QtWidgets/QListWidget-currentRowChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.currentTextChanged
        :args:
            str
        :description: QtWidgets/QListWidget-currentTextChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.itemActivated
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemActivated-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.itemChanged
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.itemClicked
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemClicked-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.itemDoubleClicked
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemDoubleClicked-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.itemEntered
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemEntered-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.itemPressed
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QListWidgetItem`
        :description: QtWidgets/QListWidget-itemPressed-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QListWidget.itemSelectionChanged
        :description: QtWidgets/QListWidget-itemSelectionChanged-s.rst
