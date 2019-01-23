.. sip:method-description::
    :status: todo
    :pysig: 452a41bd36f412e3975fab3515af9cf7
    :realsig: (int,int,const QModelIndex&)
    :digest: be1cf1a070e3842ed3e31aca9286d33f

On models that support this, removes *count* rows starting with the given *row* under parent *parent* from the model.

Returns ``true`` if the rows were successfully removed; otherwise returns ``false``.

The base class implementation does nothing and returns ``false``.

If you implement your own model, you can reimplement this function if you want to support removing. Alternatively, you can provide your own API for altering the data.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.removeRow`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.removeColumns`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.insertColumns`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.beginRemoveRows`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.endRemoveRows`.
