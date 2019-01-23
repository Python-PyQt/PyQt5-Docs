.. sip:method-description::
    :status: todo
    :pysig: 96534cfe8f59699bbf26e261591775bf
    :realsig: (const QStandardItem*) const
    :digest: f487f823a724e44af2760d2d45f7a2ac

Returns the :sip:ref:`~PyQt5.QtCore.QModelIndex` associated with the given *item*.

Use this function when you want to perform an operation that requires the :sip:ref:`~PyQt5.QtCore.QModelIndex` of the item, such as QAbstractItemView::scrollTo(). :sip:ref:`~PyQt5.QtGui.QStandardItem.index` is provided as convenience; it is equivalent to calling this function.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItemModel.itemFromIndex`, :sip:ref:`~PyQt5.QtGui.QStandardItem.index`.
