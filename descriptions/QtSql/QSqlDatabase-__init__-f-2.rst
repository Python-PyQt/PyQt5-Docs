.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 8670aa1d68b9b685165b713ce20db4a2

This is an overloaded function.

Creates a :sip:ref:`~PyQt5.QtSql.QSqlDatabase` connection that uses the driver referred to by *type*. If the *type* is not recognized, the database connection will have no functionality.

The currently available driver types are:

+-------------+---------------------------------------------+
| Driver Type | Description                                 |
+=============+=============================================+
| QDB2        | IBM DB2                                     |
+-------------+---------------------------------------------+
| QIBASE      | Borland InterBase Driver                    |
+-------------+---------------------------------------------+
| QMYSQL      | MySQL Driver                                |
+-------------+---------------------------------------------+
| QOCI        | Oracle Call Interface Driver                |
+-------------+---------------------------------------------+
| QODBC       | ODBC Driver (includes Microsoft SQL Server) |
+-------------+---------------------------------------------+
| QPSQL       | PostgreSQL Driver                           |
+-------------+---------------------------------------------+
| QSQLITE     | SQLite version 3 or above                   |
+-------------+---------------------------------------------+
| QSQLITE2    | SQLite version 2                            |
+-------------+---------------------------------------------+
| QTDS        | Sybase Adaptive Server                      |
+-------------+---------------------------------------------+

Additional third party drivers, including your own custom drivers, can be loaded dynamically.

.. seealso:: `SQL Database Drivers <https://doc.qt.io/qt-5/sql-driver.html>`_, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.registerSqlDriver`, :sip:ref:`~PyQt5.QtSql.QSqlDatabase.drivers`.
