.. sip:method-description::
    :status: todo
    :pysig: 370f92ea5f397b964fe3da6e5c545353
    :realsig: (int,int,QStandardItem*)
    :digest: 9c88b2ae0f16f52f0528aa8c1810ae8c

Sets the child item at (\ *row*, *column*) to *item*. This item (the parent item) takes ownership of *item*. If necessary, the row count and column count are increased to fit the item.

**Note:** Passing a null pointer as *item* removes the item.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItem.child`.
