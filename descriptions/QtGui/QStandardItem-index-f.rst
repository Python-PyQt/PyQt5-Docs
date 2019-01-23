.. sip:method-description::
    :status: todo
    :pysig: 2d99125b2256d2b6c1325ed8ea79240a
    :realsig: () const
    :digest: a30c55453305fc96abd3a01610ede09b

Returns the :sip:ref:`~PyQt5.QtCore.QModelIndex` associated with this item.

When you need to invoke item functionality in a :sip:ref:`~PyQt5.QtCore.QModelIndex`-based API (e.g. QAbstractItemView), you can call this function to obtain an index that corresponds to the item's location in the model.

If the item is not associated with a model, an invalid :sip:ref:`~PyQt5.QtCore.QModelIndex` is returned.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItem.model`, :sip:ref:`~PyQt5.QtGui.QStandardItemModel.itemFromIndex`.
