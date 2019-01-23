.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 4b1db4f9eec234060609650139c6c0d1

Sets the connection's user name to *name*. To have effect, the user name must be set *before* the connection is :sip:ref:`~PyQt5.QtSql.QSqlDatabase.open`. Alternatively, you can :sip:ref:`~PyQt5.QtSql.QSqlDatabase.close` the connection, set the user name, and call :sip:ref:`~PyQt5.QtSql.QSqlDatabase.open` again.

There is no default value.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDatabase.userName`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setDatabaseName`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setPassword`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setHostName`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setPort`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.setConnectOptions`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.open`.
