:orphan:

.. sip:class:: PyQt5.QtCore.QAbstractProxyModel
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
    :description: QtCore/QAbstractProxyModel-c.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QAbstractProxyModel-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.buddy
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QAbstractProxyModel-buddy-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.canDropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-canDropMimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.canFetchMore
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-canFetchMore-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.data
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole`
        :returns:
            Any
        :description: QtCore/QAbstractProxyModel-data-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.dropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.fetchMore
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QAbstractProxyModel-fetchMore-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.flags
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemFlags`
        :description: QtCore/QAbstractProxyModel-flags-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.hasChildren
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-hasChildren-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.headerData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole`
        :returns:
            Any
        :description: QtCore/QAbstractProxyModel-headerData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.itemData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            Dict[int, Any]
        :description: QtCore/QAbstractProxyModel-itemData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.mapFromSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QAbstractProxyModel-mapFromSource-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.mapSelectionFromSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :description: QtCore/QAbstractProxyModel-mapSelectionFromSource-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.mapSelectionToSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :description: QtCore/QAbstractProxyModel-mapSelectionToSource-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.mapToSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QAbstractProxyModel-mapToSource-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.mimeData
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QModelIndex`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :description: QtCore/QAbstractProxyModel-mimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.mimeTypes
        :returns:
            List[str]
        :description: QtCore/QAbstractProxyModel-mimeTypes-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.resetInternalData
        :description: QtCore/QAbstractProxyModel-resetInternalData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.revert
        :description: QtCore/QAbstractProxyModel-revert-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.setData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Any
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole`
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-setData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.setHeaderData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            Any
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole`
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-setHeaderData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.setItemData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Dict[int, Any]
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-setItemData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.setSourceModel
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
        :description: QtCore/QAbstractProxyModel-setSourceModel-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.sibling
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QAbstractProxyModel-sibling-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.sort
        :args:
            int
            order: :sip:ref:`~PyQt5.QtCore.Qt.SortOrder` = :sip:ref:`~PyQt5.QtCore.Qt.SortOrder.AscendingOrder`
        :description: QtCore/QAbstractProxyModel-sort-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.sourceModel
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
        :description: QtCore/QAbstractProxyModel-sourceModel-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.span
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtCore/QAbstractProxyModel-span-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.submit
        :returns:
            bool
        :description: QtCore/QAbstractProxyModel-submit-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.supportedDragActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtCore/QAbstractProxyModel-supportedDragActions-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractProxyModel.supportedDropActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtCore/QAbstractProxyModel-supportedDropActions-f.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractProxyModel.sourceModelChanged
        :description: QtCore/QAbstractProxyModel-sourceModelChanged-s.rst
