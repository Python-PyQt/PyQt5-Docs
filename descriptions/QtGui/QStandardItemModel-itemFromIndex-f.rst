.. sip:method-description::
    :status: todo
    :pysig: 753c65666bbec720c57605f516bedcbe
    :realsig: (const QModelIndex&) const
    :digest: 9c138a5fab97e40b7fcd6470ddacd447

Returns a pointer to the :sip:ref:`~PyQt5.QtGui.QStandardItem` associated with the given *index*.

Calling this function is typically the initial step when processing :sip:ref:`~PyQt5.QtCore.QModelIndex`-based signals from a view, such as QAbstractItemView::activated(). In your slot, you call , with the :sip:ref:`~PyQt5.QtCore.QModelIndex` carried by the signal as argument, to obtain a pointer to the corresponding :sip:ref:`~PyQt5.QtGui.QStandardItem`.

Note that this function will lazily create an item for the index (using :sip:ref:`~PyQt5.QtGui.QStandardItemModel.itemPrototype`), and set it in the parent item's child table, if no item already exists at that index.

If *index* is an invalid index, this function returns 0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItemModel.indexFromItem`.
