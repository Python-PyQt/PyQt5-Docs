.. sip:method-description::
    :status: todo
    :pysig: 8f0c99d90f9a6f08f4c91b529774d824
    :realsig: (const QString&,bool)
    :digest: f02efc9546c073fdab358c1bccc70082

Returns the database connection called *connectionName*. The database connection must have been previously added with :sip:ref:`~PyQt5.QtSql.QSqlDatabase.addDatabase`. If *open* is true (the default) and the database connection is not already open it is opened now. If no *connectionName* is specified the default connection is used. If *connectionName* does not exist in the list of databases, an invalid connection is returned.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDatabase.isOpen`.
