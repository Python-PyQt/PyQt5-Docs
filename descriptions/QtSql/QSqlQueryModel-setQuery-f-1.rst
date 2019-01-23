.. sip:method-description::
    :status: todo
    :pysig: 89a61fc97189d41460340ca03bd52ec2
    :realsig: (const QString&,const QSqlDatabase&)
    :digest: 382059f673164533c1ed17cbef2311c0

This is an overloaded function.

Executes the query *query* for the given database connection *db*. If no database (or an invalid database) is specified, the default connection is used.

:sip:ref:`~PyQt5.QtSql.QSqlQueryModel.lastError` can be used to retrieve verbose information if there was an error setting the query.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-code-src_sql_models_qsqlquerymodel.py
    :lines: 60-63

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlQueryModel.query`, :sip:ref:`~PyQt5.QtSql.QSqlQueryModel.queryChange`, :sip:ref:`~PyQt5.QtSql.QSqlQueryModel.lastError`.
