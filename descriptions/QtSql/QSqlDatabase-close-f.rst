.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 3f35e6e725df65831e253323d65139e3

Closes the database connection, freeing any resources acquired, and invalidating any existing :sip:ref:`~PyQt5.QtSql.QSqlQuery` objects that are used with the database.

This will also affect copies of this :sip:ref:`~PyQt5.QtSql.QSqlDatabase` object.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDatabase.removeDatabase`.
