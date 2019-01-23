:orphan:

.. sip:class:: PyQt5.QtCore.QAbstractListModel
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
    :description: QtCore/QAbstractListModel-c.rst

    .. sip:method:: PyQt5.QtCore.QAbstractListModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QAbstractListModel-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractListModel.dropMimeData
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
            :sip:ref:`~PyQt5.QtCore.Qt.DropAction`
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            bool
        :description: QtCore/QAbstractListModel-dropMimeData-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractListModel.flags
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemFlags`
        :description: QtCore/QAbstractListModel-flags-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractListModel.index
        :args:
            int
            column: int = 0
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QAbstractListModel-index-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractListModel.parent
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QAbstractListModel-parent-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractListModel.sibling
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QAbstractListModel-sibling-f.rst
