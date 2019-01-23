.. sip:method-description::
    :status: todo
    :pysig: ce9c31b2a069ea631e1e013247b47365
    :realsig: (const QString&,QSqlDriver::IdentifierType) const
    :digest: 7274f9ac4622441fb67ae361d2d07c7e

Returns the *identifier* escaped according to the database rules. *identifier* can either be a table name or field name, dependent on *type*.

The default implementation does nothing.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDriver.isIdentifierEscaped`.
