.. sip:method-description::
    :status: todo
    :pysig: 68ec4e6022b5c4ce812f0af5b5e646e2
    :realsig: (int,const QModelIndex&) const
    :digest: 90c2f5bb1e2fc68e18a36dcffaec589e

Returns ``true`` if all items are selected in the *row* with the given *parent*.

Note that this function is usually faster than calling :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.isSelected` on all items in the same row and that unselectable items are ignored.
