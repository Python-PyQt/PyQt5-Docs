.. sip:method-description::
    :status: todo
    :pysig: 34573dc431849f4528f41d6af17df1b7
    :realsig: (const QModelIndex&,int,int,const QModelIndex&,int)
    :digest: 155d1a7086adde7f3e9d7ce833e46211

On models that support this, moves *count* columns starting with the given *sourceColumn* under parent *sourceParent* to column *destinationChild* under parent *destinationParent*.

Returns ``true`` if the columns were successfully moved; otherwise returns ``false``.

The base class implementation does nothing and returns ``false``.

If you implement your own model, you can reimplement this function if you want to support moving. Alternatively, you can provide your own API for altering the data.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.beginMoveColumns`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.endMoveColumns`.
