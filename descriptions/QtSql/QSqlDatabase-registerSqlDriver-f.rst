.. sip:method-description::
    :status: todo
    :pysig: 28d35f9a72e17890b7109120a088c01f
    :realsig: (const QString&,QSqlDriverCreatorBase*)
    :digest: 98eb47810c1214524bb03e984c2dd9a8

This function registers a new SQL driver called *name*, within the SQL framework. This is useful if you have a custom SQL driver and don't want to compile it as a plugin.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-code-src_sql_kernel_qsqldatabase.py
    :lines: 75-77

:sip:ref:`~PyQt5.QtSql.QSqlDatabase` takes ownership of the *creator* pointer, so you mustn't delete it yourself.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDatabase.drivers`.
