.. sip:enum-description::
    :status: todo
    :digest: 50a935175b9109bb41abb47ba33154a9

This enum describes the properties of an item:

Note that checkable items need to be given both a suitable set of flags and an initial state, indicating whether the item is checked or not. This is handled automatically for model/view components, but needs to be explicitly set for instances of QListWidgetItem, QTableWidgetItem, and QTreeWidgetItem.

Note that it is undefined behavior to reimplement :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.hasChildren` to return true for an index if that index has the Qt::ItemNeverHasChildren flag set.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`.
