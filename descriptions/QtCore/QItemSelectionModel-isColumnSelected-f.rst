.. sip:method-description::
    :status: todo
    :pysig: 68ec4e6022b5c4ce812f0af5b5e646e2
    :realsig: (int,const QModelIndex&) const
    :digest: a769ccf13f177a336b81bd3d75846917

Returns ``true`` if all items are selected in the *column* with the given *parent*.

Note that this function is usually faster than calling :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.isSelected` on all items in the same column and that unselectable items are ignored.
