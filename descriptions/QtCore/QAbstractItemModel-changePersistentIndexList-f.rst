.. sip:method-description::
    :status: todo
    :pysig: 91fb35cbf92dac52c7a986a32c884a48
    :realsig: (const QModelIndexList&,const QModelIndexList&)
    :digest: 39ae728a6222fd9b61b7092ef45d2a7a

Changes the {\ :sip:ref:`~PyQt5.QtCore.QPersistentModelIndex`}es that are equal to the indexes in the given *from* model index list to the given *to* model index list.

If no persistent model indexes equal to the indexes in the given *from* model index list are found, nothing is changed.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.persistentIndexList`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.changePersistentIndex`.
