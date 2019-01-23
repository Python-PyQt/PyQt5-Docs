.. sip:method-description::
    :status: todo
    :pysig: 452a41bd36f412e3975fab3515af9cf7
    :realsig: (int,int,const QModelIndex&)
    :digest: aa10c2067711ccad0b1428ca01521ee3

On models that support this, removes *count* columns starting with the given *column* under parent *parent* from the model.

Returns ``true`` if the columns were successfully removed; otherwise returns ``false``.

The base class implementation does nothing and returns ``false``.

If you implement your own model, you can reimplement this function if you want to support removing. Alternatively, you can provide your own API for altering the data.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.removeColumn`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.removeRows`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.insertColumns`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.beginRemoveColumns`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.endRemoveColumns`.
