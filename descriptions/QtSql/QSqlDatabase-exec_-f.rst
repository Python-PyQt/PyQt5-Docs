.. sip:method-description::
    :status: todo
    :pysig: b66ab594083fb7d335512862fc60b66e
    :realname: QSqlDatabase::exec
    :realsig: (const QString&) const
    :digest: 52e3a2b0b2334b76a412617895b2bb92

Executes a SQL statement on the database and returns a :sip:ref:`~PyQt5.QtSql.QSqlQuery` object. Use :sip:ref:`~PyQt5.QtSql.QSqlDatabase.lastError` to retrieve error information. If *query* is empty, an empty, invalid query is returned and :sip:ref:`~PyQt5.QtSql.QSqlDatabase.lastError` is not affected.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlQuery`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.lastError`.
