.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 7d4022e54a313165b2deb4a414b6db60

Sets the connection's database name to *name*. To have effect, the database name must be set *before* the connection is :sip:ref:`~PyQt5.QtSql.QSqlDatabase.open`. Alternatively, you can :sip:ref:`~PyQt5.QtSql.QSqlDatabase.close` the connection, set the database name, and call :sip:ref:`~PyQt5.QtSql.QSqlDatabase.open` again.

**Note:** The *database name* is not the *connection name*. The connection name must be passed to :sip:ref:`~PyQt5.QtSql.QSqlDatabase.addDatabase` at connection object create time.

For the QOCI (Oracle) driver, the database name is the TNS Service Name.

For the QODBC driver, the *name* can either be a DSN, a DSN filename (in which case the file must have a ``.dsn`` extension), or a connection string.

For example, Microsoft Access users can use the following connection string to open an ``.mdb`` file directly, instead of having to create a DSN entry in the ODBC manager:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-code-src_sql_kernel_qsqldatabase.py
    :lines: 82-88

There is no default value.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDatabase.databaseName`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setUserName`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setPassword`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setHostName`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setPort`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setConnectOptions`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.open`.
