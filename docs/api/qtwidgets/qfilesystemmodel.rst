:orphan:

.. sip:class:: PyQt5.QtWidgets.QFileSystemModel
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
    :description: QtWidgets/QFileSystemModel-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QFileSystemModel.Option
        :description: QtWidgets/QFileSystemModel-Option-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileSystemModel.Option.DontResolveSymlinks
            :description: QtWidgets/QFileSystemModel-Option-DontResolveSymlinks-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileSystemModel.Option.DontUseCustomDirectoryIcons
            :description: QtWidgets/QFileSystemModel-Option-DontUseCustomDirectoryIcons-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileSystemModel.Option.DontWatchForChanges
            :description: QtWidgets/QFileSystemModel-Option-DontWatchForChanges-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QFileSystemModel.Roles
        :description: QtWidgets/QFileSystemModel-Roles-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileSystemModel.Roles.FileIconRole
            :description: QtWidgets/QFileSystemModel-Roles-FileIconRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileSystemModel.Roles.FileNameRole
            :description: QtWidgets/QFileSystemModel-Roles-FileNameRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileSystemModel.Roles.FilePathRole
            :description: QtWidgets/QFileSystemModel-Roles-FilePathRole-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileSystemModel.Roles.FilePermissions
            :description: QtWidgets/QFileSystemModel-Roles-FilePermissions-v.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QFileSystemModel-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.canFetchMore
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-canFetchMore-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.columnCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtWidgets/QFileSystemModel-columnCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.data
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            role: int = Qt.ItemDataRole.DisplayRole
        :returns:
            Any
        :description: QtWidgets/QFileSystemModel-data-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.dropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.fetchMore
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QFileSystemModel-fetchMore-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.fileIcon
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QFileSystemModel-fileIcon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.fileInfo
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QFileInfo`
        :description: QtWidgets/QFileSystemModel-fileInfo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.fileName
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            str
        :description: QtWidgets/QFileSystemModel-fileName-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.filePath
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            str
        :description: QtWidgets/QFileSystemModel-filePath-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.filter
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDir.Filters`
        :description: QtWidgets/QFileSystemModel-filter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.flags
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemFlags`
        :description: QtWidgets/QFileSystemModel-flags-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.hasChildren
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-hasChildren-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.headerData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            role: int = Qt.ItemDataRole.DisplayRole
        :returns:
            Any
        :description: QtWidgets/QFileSystemModel-headerData-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.iconProvider
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFileIconProvider`
        :description: QtWidgets/QFileSystemModel-iconProvider-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.index
        :args:
            str
            column: int = 0
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QFileSystemModel-index-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.index
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QFileSystemModel-index-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.isDir
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-isDir-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.isReadOnly
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-isReadOnly-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.lastModified
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtWidgets/QFileSystemModel-lastModified-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.mimeData
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QModelIndex`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :description: QtWidgets/QFileSystemModel-mimeData-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.mimeTypes
        :returns:
            List[str]
        :description: QtWidgets/QFileSystemModel-mimeTypes-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.mkdir
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QFileSystemModel-mkdir-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.myComputer
        :args:
            role: int = Qt.ItemDataRole.DisplayRole
        :returns:
            Any
        :description: QtWidgets/QFileSystemModel-myComputer-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.nameFilterDisables
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-nameFilterDisables-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.nameFilters
        :returns:
            List[str]
        :description: QtWidgets/QFileSystemModel-nameFilters-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.options
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFileSystemModel.Options`
        :description: QtWidgets/QFileSystemModel-options-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.parent
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QFileSystemModel-parent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.permissions
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QFileDevice.Permissions`
        :description: QtWidgets/QFileSystemModel-permissions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.remove
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-remove-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.resolveSymlinks
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-resolveSymlinks-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.rmdir
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-rmdir-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.rootDirectory
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDir`
        :description: QtWidgets/QFileSystemModel-rootDirectory-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.rootPath
        :returns:
            str
        :description: QtWidgets/QFileSystemModel-rootPath-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.rowCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtWidgets/QFileSystemModel-rowCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Any
            role: int = Qt.ItemDataRole.EditRole
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-setData-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setFilter
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDir.Filters`, :sip:ref:`~PyQt5.QtCore.QDir.Filter`]
        :description: QtWidgets/QFileSystemModel-setFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setIconProvider
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFileIconProvider`
        :description: QtWidgets/QFileSystemModel-setIconProvider-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setNameFilterDisables
        :args:
            bool
        :description: QtWidgets/QFileSystemModel-setNameFilterDisables-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setNameFilters
        :args:
            Iterable[str]
        :description: QtWidgets/QFileSystemModel-setNameFilters-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFileSystemModel.Option`
            on: bool = True
        :description: QtWidgets/QFileSystemModel-setOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QFileSystemModel.Options`, :sip:ref:`~PyQt5.QtWidgets.QFileSystemModel.Option`]
        :description: QtWidgets/QFileSystemModel-setOptions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setReadOnly
        :args:
            bool
        :description: QtWidgets/QFileSystemModel-setReadOnly-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setResolveSymlinks
        :args:
            bool
        :description: QtWidgets/QFileSystemModel-setResolveSymlinks-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.setRootPath
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QFileSystemModel-setRootPath-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.sibling
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtWidgets/QFileSystemModel-sibling-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.size
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            int
        :description: QtWidgets/QFileSystemModel-size-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.sort
        :args:
            int
            order: :sip:ref:`~PyQt5.QtCore.Qt.SortOrder` = :sip:ref:`~PyQt5.QtCore.Qt.SortOrder.AscendingOrder`
        :description: QtWidgets/QFileSystemModel-sort-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.supportedDropActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtWidgets/QFileSystemModel-supportedDropActions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.testOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFileSystemModel.Option`
        :returns:
            bool
        :description: QtWidgets/QFileSystemModel-testOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtWidgets/QFileSystemModel-timerEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileSystemModel.type
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            str
        :description: QtWidgets/QFileSystemModel-type-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QFileSystemModel.directoryLoaded
        :args:
            str
        :description: QtWidgets/QFileSystemModel-directoryLoaded-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QFileSystemModel.fileRenamed
        :args:
            str
            str
            str
        :description: QtWidgets/QFileSystemModel-fileRenamed-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QFileSystemModel.rootPathChanged
        :args:
            str
        :description: QtWidgets/QFileSystemModel-rootPathChanged-s.rst
