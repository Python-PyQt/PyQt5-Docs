.. sip:method-description::
    :status: todo
    :pysig: fabef6d563b8236177cf37cc85411b02
    :realsig: (int) const
    :digest: a006deb4fe19cd50cee7ac44e10395cb

Returns a :sip:ref:`~PyQt5.QtSql.QSqlTableModel` object for accessing the table for which *column* is a foreign key, or 0 if there is no relation for the given *column*.

The returned object is owned by the :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel`.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel.setRelation`, :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel.relation`.
