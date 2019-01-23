.. sip:class-description::
    :status: todo
    :brief: Means of executing and manipulating SQL statements
    :digest: 2b8144775fe8b9080cef9bc61f370424

The :sip:ref:`~PyQt5.QtSql.QSqlQuery` class provides a means of executing and manipulating SQL statements.

:sip:ref:`~PyQt5.QtSql.QSqlQuery` encapsulates the functionality involved in creating, navigating and retrieving data from SQL queries which are executed on a :sip:ref:`~PyQt5.QtSql.QSqlDatabase`. It can be used to execute DML (data manipulation language) statements, such as ``SELECT``, ``INSERT``, ``UPDATE`` and ``DELETE``, as well as DDL (data definition language) statements, such as ``CREATE`` ``TABLE``. It can also be used to execute database-specific commands which are not standard SQL (e.g. ``SET DATESTYLE=ISO`` for PostgreSQL).

Successfully executed SQL statements set the query's state to active so that :sip:ref:`~PyQt5.QtSql.QSqlQuery.isActive` returns ``true``. Otherwise the query's state is set to inactive. In either case, when executing a new SQL statement, the query is positioned on an invalid record. An active query must be navigated to a valid record (so that :sip:ref:`~PyQt5.QtSql.QSqlQuery.isValid` returns ``true``) before values can be retrieved.

For some databases, if an active query that is a ``SELECT`` statement exists when you call :sip:ref:`~PyQt5.QtSql.QSqlDatabase.commit` or :sip:ref:`~PyQt5.QtSql.QSqlDatabase.rollback`, the commit or rollback will fail. See :sip:ref:`~PyQt5.QtSql.QSqlQuery.isActive` for details.

.. _qsqlquery-qsqlquery-examples:

Navigating records is performed with the following functions:

* :sip:ref:`~PyQt5.QtSql.QSqlQuery.next`

* :sip:ref:`~PyQt5.QtSql.QSqlQuery.previous`

* :sip:ref:`~PyQt5.QtSql.QSqlQuery.first`

* :sip:ref:`~PyQt5.QtSql.QSqlQuery.last`

* :sip:ref:`~PyQt5.QtSql.QSqlQuery.seek`

These functions allow the programmer to move forward, backward or arbitrarily through the records returned by the query. If you only need to move forward through the results (e.g., by using :sip:ref:`~PyQt5.QtSql.QSqlQuery.next`), you can use :sip:ref:`~PyQt5.QtSql.QSqlQuery.setForwardOnly`, which will save a significant amount of memory overhead and improve performance on some databases. Once an active query is positioned on a valid record, data can be retrieved using :sip:ref:`~PyQt5.QtSql.QSqlQuery.value`. All data is transferred from the SQL backend using QVariants.

For example:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 124-128

To access the data returned by a query, use value(int). Each field in the data returned by a ``SELECT`` statement is accessed by passing the field's position in the statement, starting from 0. This makes using ``SELECT \*`` queries inadvisable because the order of the fields returned is indeterminate.

For the sake of efficiency, there are no functions to access a field by name (unless you use prepared queries with names, as explained below). To convert a field name into an index, use :sip:ref:`~PyQt5.QtSql.QSqlQuery.record`.\ :sip:ref:`~PyQt5.QtSql.QSqlRecord.indexOf`, for example:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 135-140

:sip:ref:`~PyQt5.QtSql.QSqlQuery` supports prepared query execution and the binding of parameter values to placeholders. Some databases don't support these features, so for those, Qt emulates the required functionality. For example, the Oracle and ODBC drivers have proper prepared query support, and Qt makes use of it; but for databases that don't have this support, Qt implements the feature itself, e.g. by replacing placeholders with actual values when a query is executed. Use :sip:ref:`~PyQt5.QtSql.QSqlQuery.numRowsAffected` to find out how many rows were affected by a non-``SELECT`` query, and :sip:ref:`~PyQt5.QtSql.QSqlQuery.size` to find how many were retrieved by a ``SELECT``.

Oracle databases identify placeholders by using a colon-name syntax, e.g ``:name``. ODBC simply uses ``?`` characters. Qt supports both syntaxes, with the restriction that you can't mix them in the same query.

You can retrieve the values of all the fields in a single variable (a map) using :sip:ref:`~PyQt5.QtSql.QSqlQuery.boundValues`.

.. _qsqlquery-approaches-to-binding-values:

Approaches to Binding Values
----------------------------

Below we present the same example using each of the four different binding approaches, as well as one example of binding values to a stored procedure.

**Named binding using named placeholders:**

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 147-153

**Positional binding using named placeholders:**

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 160-166

**Binding values using positional placeholders (version 1):**

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 173-179

**Binding values using positional placeholders (version 2):**

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 186-192

**Binding values to a stored procedure:**

This code calls a stored procedure called ``AsciiToInt()``, passing it a character through its in parameter, and taking its result in the out parameter.

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 199-204

Note that unbound parameters will retain their values.

Stored procedures that uses the return statement to return values, or return multiple result sets, are not fully supported. For specific details see `SQL Database Drivers <https://doc.qt.io/qt-5/sql-driver.html>`_.

**Warning:** You must load the SQL driver and open the connection before a :sip:ref:`~PyQt5.QtSql.QSqlQuery` is created. Also, the connection must remain open while the query exists; otherwise, the behavior of :sip:ref:`~PyQt5.QtSql.QSqlQuery` is undefined.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDatabase`, :sip:ref:`~PyQt5.QtSql.QSqlQueryModel`, :sip:ref:`~PyQt5.QtSql.QSqlTableModel`, :sip:ref:`~PyQt5.QtCore.QVariant`.
