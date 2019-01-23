.. sip:method-description::
    :status: todo
    :pysig: 132ef9df1f4642ade15be878398fab29
    :realsig: (int) const
    :digest: 8ff32d24f1b7a74bb4a8efb3afcb7b22

Returns the item's data for the given *role*, or an invalid :sip:ref:`~PyQt5.QtCore.QVariant` if there is no data for the role.

**Note:** The default implementation treats :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole` and :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole` as referring to the same data.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItem.setData`.
