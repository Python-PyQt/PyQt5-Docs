.. sip:method-description::
    :status: todo
    :pysig: 4bac66f8cc2204f29f6fc05cb5a9813e
    :realsig: (const QModelIndex&) const
    :digest: db0b22f5f1498aa08182ebaa02a3004d

Returns the index of the value in the database result set for the given *item* in the model.

The return value is identical to *item* if no columns or rows have been inserted, removed, or moved around.

Returns an invalid model index if *item* is out of bounds or if *item* does not point to a value in the result set.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlQueryModel.indexInQuery`.
