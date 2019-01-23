.. sip:method-description::
    :status: todo
    :pysig: 370f92ea5f397b964fe3da6e5c545353
    :realsig: (int,int,QStandardItem*)
    :digest: 7ab7b451434cde099e258ed4841656a6

Sets the item for the given *row* and *column* to *item*. The model takes ownership of the item. If necessary, the row count and column count are increased to fit the item. The previous item at the given location (if there was one) is deleted.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItemModel.item`.
