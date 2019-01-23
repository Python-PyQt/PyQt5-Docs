.. sip:method-description::
    :status: todo
    :pysig: 452a41bd36f412e3975fab3515af9cf7
    :realsig: (int,int,const QModelIndex&)
    :digest: 05f5003017e847e12aa866da8523c58a

On models that support this, inserts *count* new columns into the model before the given *column*. The items in each new column will be children of the item represented by the *parent* model index.

If *column* is 0, the columns are prepended to any existing columns.

If *column* is :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.columnCount`, the columns are appended to any existing columns.

If *parent* has no children, a single row with *count* columns is inserted.

Returns ``true`` if the columns were successfully inserted; otherwise returns ``false``.

The base class implementation does nothing and returns ``false``.

If you implement your own model, you can reimplement this function if you want to support insertions. Alternatively, you can provide your own API for altering the data.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.insertRows`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.removeColumns`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.beginInsertColumns`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.endInsertColumns`.
