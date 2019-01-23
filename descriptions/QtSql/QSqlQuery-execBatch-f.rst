.. sip:method-description::
    :status: todo
    :pysig: 1b3582697406c797ae14504de9067bdc
    :realsig: (QSqlQuery::BatchExecutionMode)
    :digest: ab2fc64d645565baa7a0db6d6b3d8e88

Executes a previously prepared SQL query in a batch. All the bound parameters have to be lists of variants. If the database doesn't support batch executions, the driver will simulate it using conventional :sip:ref:`~PyQt5.QtSql.QSqlQuery.exec` calls.

Returns ``true`` if the query is executed successfully; otherwise returns ``false``.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-code-src_sql_kernel_qsqlquery.py
    :lines: 71-83

The example above inserts four new rows into ``myTable``:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-code-src_sql_kernel_qsqlquery.py
    :lines: 88-91

To bind NULL values, a null :sip:ref:`~PyQt5.QtCore.QVariant` of the relevant type has to be added to the bound QVariantList; for example, ``QVariant(QVariant::String)`` should be used if you are using strings.

**Note:** Every bound QVariantList must contain the same amount of variants.

**Note:** The type of the QVariants in a list must not change. For example, you cannot mix integer and string variants within a QVariantList.

The *mode* parameter indicates how the bound QVariantList will be interpreted. If *mode* is ``ValuesAsRows``, every variant within the QVariantList will be interpreted as a value for a new row. ``ValuesAsColumns`` is a special case for the Oracle driver. In this mode, every entry within a QVariantList will be interpreted as array-value for an IN or OUT value within a stored procedure. Note that this will only work if the IN or OUT value is a table-type consisting of only one column of a basic type, for example ``TYPE myType IS TABLE OF VARCHAR(64) INDEX BY BINARY_INTEGER;``

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlQuery.prepare`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.bindValue`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.addBindValue`.
