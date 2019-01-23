.. sip:method-description::
    :status: todo
    :pysig: 5d0d43b69c6db723f43e1ce6a2fbc329
    :realsig: (const QModelIndex&) const
    :digest: 348dfa6226a4f076d672d57246b6bbf7

Returns ``true`` if *parent* has any children; otherwise returns ``false``.

Use :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.rowCount` on the parent to find out the number of children.

Note that it is undefined behavior to report that a particular index  with this method if the same index has the flag Qt::ItemNeverHasChildren set.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.parent`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.index`.
