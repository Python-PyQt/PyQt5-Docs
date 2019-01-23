.. sip:method-description::
    :status: todo
    :pysig: 07052ac575936fd484766b00acc21668
    :realsig: (int,const QSqlRelation&)
    :digest: e21db5cc1a4b009976d5b92179431107

Lets the specified *column* be a foreign index specified by *relation*.

Example:

.. literalinclude:: ../../../snippets/qtbase-examples-sql-relationaltablemodel-relationaltablemodel.py
    :lines: 61-61

.. literalinclude:: ../../../snippets/qtbase-examples-sql-relationaltablemodel-relationaltablemodel.py
    :lines: 66-66

The  call specifies that column 2 in table ``employee`` is a foreign key that maps with field ``id`` of table ``city``, and that the view should present the ``city``'s ``name`` field to the user.

Note: The table's primary key may not contain a relation to another table.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel.relation`.
