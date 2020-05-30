:orphan:

.. sip:class:: PyQt5.QtCore.QConcatenateTablesProxyModel
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
    :description: QtCore/QConcatenateTablesProxyModel-c.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QConcatenateTablesProxyModel-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.addSourceModel
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
        :description: QtCore/QConcatenateTablesProxyModel-addSourceModel-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.canDropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QConcatenateTablesProxyModel-canDropMimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.columnCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtCore/QConcatenateTablesProxyModel-columnCount-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.data
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            role: int = Qt.ItemDataRole.DisplayRole
        :returns:
            Any
        :description: QtCore/QConcatenateTablesProxyModel-data-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.dropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QConcatenateTablesProxyModel-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.flags
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemFlags`
        :description: QtCore/QConcatenateTablesProxyModel-flags-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.headerData
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            role: int = Qt.ItemDataRole.DisplayRole
        :returns:
            Any
        :description: QtCore/QConcatenateTablesProxyModel-headerData-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.index
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QConcatenateTablesProxyModel-index-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.itemData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            Dict[int, Any]
        :description: QtCore/QConcatenateTablesProxyModel-itemData-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.mapFromSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QConcatenateTablesProxyModel-mapFromSource-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.mapToSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QConcatenateTablesProxyModel-mapToSource-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.mimeData
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QModelIndex`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :description: QtCore/QConcatenateTablesProxyModel-mimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.mimeTypes
        :returns:
            List[str]
        :description: QtCore/QConcatenateTablesProxyModel-mimeTypes-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.parent
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QConcatenateTablesProxyModel-parent-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.removeSourceModel
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
        :description: QtCore/QConcatenateTablesProxyModel-removeSourceModel-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.rowCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtCore/QConcatenateTablesProxyModel-rowCount-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.setData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Any
            role: int = Qt.ItemDataRole.EditRole
        :returns:
            bool
        :description: QtCore/QConcatenateTablesProxyModel-setData-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.setItemData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Dict[int, Any]
        :returns:
            bool
        :description: QtCore/QConcatenateTablesProxyModel-setItemData-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.sourceModels
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QAbstractItemModel`]
        :description: QtCore/QConcatenateTablesProxyModel-sourceModels-f.rst

    .. sip:method:: PyQt5.QtCore.QConcatenateTablesProxyModel.span
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtCore/QConcatenateTablesProxyModel-span-f.rst
