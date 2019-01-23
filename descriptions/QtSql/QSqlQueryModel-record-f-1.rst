.. sip:method-description::
    :status: todo
    :pysig: 977adeec77c5f98e6799e1553345f04f
    :realsig: (int) const
    :digest: 78a9f27f442d7fbcace7db84e6342538

Returns the record containing information about the fields of the current query. If *row* is the index of a valid row, the record will be populated with values from that row.

If the model is not initialized, an empty record will be returned.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlRecord.isEmpty`.
