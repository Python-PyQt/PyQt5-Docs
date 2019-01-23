.. sip:method-description::
    :status: todo
    :pysig: 0f30cb18edfba20518f79f42017618b2
    :realsig: (QAbstractItemModel*)
    :digest: 40d4a79d6505bc9452e351598da6f80b

Sets the given *sourceModel* to be processed by the proxy model.

Subclasses should call beginResetModel() at the beginning of the method, disconnect from the old model, call this method, connect to the new model, and call endResetModel().

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractProxyModel.sourceModel`.
