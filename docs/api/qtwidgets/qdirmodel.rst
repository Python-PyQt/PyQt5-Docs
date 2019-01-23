:orphan:

.. sip:class:: PyQt5.QtWidgets.QDirModel
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
    :description: QtWidgets/QDirModel-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QDirModel.Roles
        :description: QtWidgets/QDirModel-Roles-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDirModel.Roles.FileIconRole
            :description: QtWidgets/QDirModel-Roles-FileIconRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDirModel.Roles.FileNameRole
            :description: QtWidgets/QDirModel-Roles-FileNameRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDirModel.Roles.FilePathRole
            :description: QtWidgets/QDirModel-Roles-FilePathRole-v.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QDirModel-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.__init__
        :args:
            Iterable[str]
            Union[:sip:ref:`~PyQt5.QtCore.QDir.Filters`, :sip:ref:`~PyQt5.QtCore.QDir.Filter`]
            Union[:sip:ref:`~PyQt5.QtCore.QDir.SortFlags`, :sip:ref:`~PyQt5.QtCore.QDir.SortFlag`]
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QDirModel-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.columnCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtWidgets/QDirModel-columnCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.data
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole`
        :returns:
            Any
        :description: QtWidgets/QDirModel-data-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.dropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QDirModel-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.fileIcon
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QDirModel-fileIcon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.fileInfo
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QFileInfo`
        :description: QtWidgets/QDirModel-fileInfo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.fileName
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            str
        :description: QtWidgets/QDirModel-fileName-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.filePath
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            str
        :description: QtWidgets/QDirModel-filePath-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.filter
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDir.Filters`
        :description: QtWidgets/QDirModel-filter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.flags
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemFlags`
        :description: QtWidgets/QDirModel-flags-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.hasChildren
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtWidgets/QDirModel-hasChildren-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.headerData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole`
        :returns:
            Any
        :description: QtWidgets/QDirModel-headerData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.iconProvider
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFileIconProvider`
        :description: QtWidgets/QDirModel-iconProvider-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.index
        :args:
            str
            column: int = 0
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QDirModel-index-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.index
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QDirModel-index-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.isDir
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QDirModel-isDir-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.isReadOnly
        :returns:
            bool
        :description: QtWidgets/QDirModel-isReadOnly-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.lazyChildCount
        :returns:
            bool
        :description: QtWidgets/QDirModel-lazyChildCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.mimeData
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QModelIndex`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :description: QtWidgets/QDirModel-mimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.mimeTypes
        :returns:
            List[str]
        :description: QtWidgets/QDirModel-mimeTypes-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.mkdir
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QDirModel-mkdir-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.nameFilters
        :returns:
            List[str]
        :description: QtWidgets/QDirModel-nameFilters-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.parent
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtWidgets/QDirModel-parent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.parent
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QDirModel-parent-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.refresh
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :description: QtWidgets/QDirModel-refresh-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.remove
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QDirModel-remove-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.resolveSymlinks
        :returns:
            bool
        :description: QtWidgets/QDirModel-resolveSymlinks-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.rmdir
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QDirModel-rmdir-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.rowCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtWidgets/QDirModel-rowCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Any
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole`
        :returns:
            bool
        :description: QtWidgets/QDirModel-setData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setFilter
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDir.Filters`, :sip:ref:`~PyQt5.QtCore.QDir.Filter`]
        :description: QtWidgets/QDirModel-setFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setIconProvider
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFileIconProvider`
        :description: QtWidgets/QDirModel-setIconProvider-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setLazyChildCount
        :args:
            bool
        :description: QtWidgets/QDirModel-setLazyChildCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setNameFilters
        :args:
            Iterable[str]
        :description: QtWidgets/QDirModel-setNameFilters-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setReadOnly
        :args:
            bool
        :description: QtWidgets/QDirModel-setReadOnly-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setResolveSymlinks
        :args:
            bool
        :description: QtWidgets/QDirModel-setResolveSymlinks-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.setSorting
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDir.SortFlags`, :sip:ref:`~PyQt5.QtCore.QDir.SortFlag`]
        :description: QtWidgets/QDirModel-setSorting-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.sort
        :args:
            int
            order: :sip:ref:`~PyQt5.QtCore.Qt.SortOrder` = :sip:ref:`~PyQt5.QtCore.Qt.SortOrder.AscendingOrder`
        :description: QtWidgets/QDirModel-sort-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.sorting
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDir.SortFlags`
        :description: QtWidgets/QDirModel-sorting-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDirModel.supportedDropActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtWidgets/QDirModel-supportedDropActions-f.rst
