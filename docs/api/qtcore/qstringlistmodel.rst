:orphan:

.. sip:class:: PyQt5.QtCore.QStringListModel
    :inherits: :sip:ref:`~PyQt5.QtCore.QAbstractListModel`
    :description: QtCore/QStringListModel-c.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QStringListModel-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.__init__
        :args:
            Iterable[str]
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QStringListModel-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.data
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            int
        :returns:
            Any
        :description: QtCore/QStringListModel-data-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.flags
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemFlags`
        :description: QtCore/QStringListModel-flags-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.insertRows
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QStringListModel-insertRows-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.removeRows
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtCore/QStringListModel-removeRows-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.rowCount
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            int
        :description: QtCore/QStringListModel-rowCount-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.setData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Any
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole`
        :returns:
            bool
        :description: QtCore/QStringListModel-setData-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.setStringList
        :args:
            Iterable[str]
        :description: QtCore/QStringListModel-setStringList-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.sibling
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
        :description: QtCore/QStringListModel-sibling-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.sort
        :args:
            int
            order: :sip:ref:`~PyQt5.QtCore.Qt.SortOrder` = :sip:ref:`~PyQt5.QtCore.Qt.SortOrder.AscendingOrder`
        :description: QtCore/QStringListModel-sort-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.stringList
        :returns:
            List[str]
        :description: QtCore/QStringListModel-stringList-f.rst

    .. sip:method:: PyQt5.QtCore.QStringListModel.supportedDropActions
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DropActions`
        :description: QtCore/QStringListModel-supportedDropActions-f.rst
