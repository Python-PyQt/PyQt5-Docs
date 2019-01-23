.. sip:method-description::
    :status: todo
    :pysig: 34573dc431849f4528f41d6af17df1b7
    :realsig: (const QModelIndex&,int,int,const QModelIndex&,int)
    :digest: 99c0d7aaba7d4051f0f28e44390ebc10

On models that support this, moves *count* rows starting with the given *sourceRow* under parent *sourceParent* to row *destinationChild* under parent *destinationParent*.

Returns ``true`` if the rows were successfully moved; otherwise returns ``false``.

The base class implementation does nothing and returns ``false``.

If you implement your own model, you can reimplement this function if you want to support moving. Alternatively, you can provide your own API for altering the data.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.beginMoveRows`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.endMoveRows`.
