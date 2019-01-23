:orphan:

.. sip:class:: PyQt5.QtCore.QSortFilterProxyModel
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractProxyModel`
    :description: QtCore/QSortFilterProxyModel-c.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QSortFilterProxyModel-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.buddy
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QSortFilterProxyModel-buddy-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.canFetchMore
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-canFetchMore-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.columnCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtCore/QSortFilterProxyModel-columnCount-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.data
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole`
        :returns:
            Any
        :description: QtCore/QSortFilterProxyModel-data-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.dropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.dynamicSortFilter
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-dynamicSortFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.fetchMore
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QSortFilterProxyModel-fetchMore-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.filterAcceptsColumn
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-filterAcceptsColumn-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.filterAcceptsRow
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-filterAcceptsRow-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.filterCaseSensitivity
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity`
        :description: QtCore/QSortFilterProxyModel-filterCaseSensitivity-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.filterKeyColumn
        :returns:
            int
        :description: QtCore/QSortFilterProxyModel-filterKeyColumn-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.filterRegExp
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRegExp`
        :description: QtCore/QSortFilterProxyModel-filterRegExp-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.filterRegularExpression
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
        :description: QtCore/QSortFilterProxyModel-filterRegularExpression-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.filterRole
        :returns:
            int
        :description: QtCore/QSortFilterProxyModel-filterRole-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.flags
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemFlags`
        :description: QtCore/QSortFilterProxyModel-flags-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.hasChildren
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-hasChildren-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.headerData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole`
        :returns:
            Any
        :description: QtCore/QSortFilterProxyModel-headerData-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.index
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QSortFilterProxyModel-index-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.insertColumns
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-insertColumns-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.insertRows
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-insertRows-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.invalidate
        :description: QtCore/QSortFilterProxyModel-invalidate-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.invalidateFilter
        :description: QtCore/QSortFilterProxyModel-invalidateFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.isRecursiveFilteringEnabled
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-isRecursiveFilteringEnabled-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.isSortLocaleAware
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-isSortLocaleAware-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.lessThan
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-lessThan-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.mapFromSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QSortFilterProxyModel-mapFromSource-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.mapSelectionFromSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :description: QtCore/QSortFilterProxyModel-mapSelectionFromSource-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.mapSelectionToSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QItemSelection`
        :description: QtCore/QSortFilterProxyModel-mapSelectionToSource-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.mapToSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QSortFilterProxyModel-mapToSource-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.match
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            int
            Any
            hits: int = 1
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.MatchFlags`, :sip:ref:`~PyQt5.QtCore.Qt.MatchFlag`] = Qt.MatchStartsWith|Qt.MatchWrap
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QModelIndex`]
        :description: QtCore/QSortFilterProxyModel-match-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.mimeData
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QModelIndex`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :description: QtCore/QSortFilterProxyModel-mimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.mimeTypes
        :returns:
            List[str]
        :description: QtCore/QSortFilterProxyModel-mimeTypes-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.parent
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QSortFilterProxyModel-parent-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.parent
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QSortFilterProxyModel-parent-f-1.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.removeColumns
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-removeColumns-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.removeRows
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-removeRows-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.rowCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtCore/QSortFilterProxyModel-rowCount-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Any
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole`
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-setData-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setDynamicSortFilter
        :args:
            bool
        :description: QtCore/QSortFilterProxyModel-setDynamicSortFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterCaseSensitivity
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity`
        :description: QtCore/QSortFilterProxyModel-setFilterCaseSensitivity-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterFixedString
        :args:
            str
        :description: QtCore/QSortFilterProxyModel-setFilterFixedString-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterKeyColumn
        :args:
            int
        :description: QtCore/QSortFilterProxyModel-setFilterKeyColumn-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterRegExp
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegExp`
        :description: QtCore/QSortFilterProxyModel-setFilterRegExp-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterRegExp
        :args:
            str
        :description: QtCore/QSortFilterProxyModel-setFilterRegExp-f-1.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterRegularExpression
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
        :description: QtCore/QSortFilterProxyModel-setFilterRegularExpression-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterRegularExpression
        :args:
            str
        :description: QtCore/QSortFilterProxyModel-setFilterRegularExpression-f-1.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterRole
        :args:
            int
        :description: QtCore/QSortFilterProxyModel-setFilterRole-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setFilterWildcard
        :args:
            str
        :description: QtCore/QSortFilterProxyModel-setFilterWildcard-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setHeaderData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            Any
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole`
        :returns:
            bool
        :description: QtCore/QSortFilterProxyModel-setHeaderData-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setRecursiveFilteringEnabled
        :args:
            bool
        :description: QtCore/QSortFilterProxyModel-setRecursiveFilteringEnabled-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setSortCaseSensitivity
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity`
        :description: QtCore/QSortFilterProxyModel-setSortCaseSensitivity-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setSortLocaleAware
        :args:
            bool
        :description: QtCore/QSortFilterProxyModel-setSortLocaleAware-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setSortRole
        :args:
            int
        :description: QtCore/QSortFilterProxyModel-setSortRole-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.setSourceModel
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
        :description: QtCore/QSortFilterProxyModel-setSourceModel-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.sibling
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QSortFilterProxyModel-sibling-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.sort
        :args:
            int
            order: :sip:ref:`~PyQt5.QtCore.Qt.SortOrder` = :sip:ref:`~PyQt5.QtCore.Qt.SortOrder.AscendingOrder`
        :description: QtCore/QSortFilterProxyModel-sort-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.sortCaseSensitivity
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity`
        :description: QtCore/QSortFilterProxyModel-sortCaseSensitivity-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.sortColumn
        :returns:
            int
        :description: QtCore/QSortFilterProxyModel-sortColumn-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.sortOrder
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.SortOrder`
        :description: QtCore/QSortFilterProxyModel-sortOrder-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.sortRole
        :returns:
            int
        :description: QtCore/QSortFilterProxyModel-sortRole-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.span
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtCore/QSortFilterProxyModel-span-f.rst

    .. sip:method:: PyQt5.QtCore.QSortFilterProxyModel.supportedDropActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtCore/QSortFilterProxyModel-supportedDropActions-f.rst
