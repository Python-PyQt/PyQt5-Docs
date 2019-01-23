.. sip:method-description::
    :status: todo
    :pysig: ed36a1ef76a59ee3f15180e0441188ad
    :realsig: () const
    :digest: b5d63f7177f3e10d5fe0efe0bdb0d4bb

Returns the low-level database handle for this result set wrapped in a :sip:ref:`~PyQt5.QtCore.QVariant` or an invalid :sip:ref:`~PyQt5.QtCore.QVariant` if there is no handle.

**Warning:** Use this with uttermost care and only if you know what you're doing.

**Warning:** The handle returned here can become a stale pointer if the result is modified (for example, if you clear it).

**Warning:** The handle can be NULL if the result was not executed yet.

**Warning:** PostgreSQL: in forward-only mode, the handle of :sip:ref:`~PyQt5.QtSql.QSqlResult` can change after calling :sip:ref:`~PyQt5.QtSql.QSqlResult.fetch`, :sip:ref:`~PyQt5.QtSql.QSqlResult.fetchFirst`, :sip:ref:`~PyQt5.QtSql.QSqlResult.fetchLast`, :sip:ref:`~PyQt5.QtSql.QSqlResult.fetchNext`, :sip:ref:`~PyQt5.QtSql.QSqlResult.fetchPrevious`, nextResult().

The handle returned here is database-dependent, you should query the type name of the variant before accessing it.

This example retrieves the handle for a sqlite result:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-code-src_sql_kernel_qsqlresult.py
    :lines: 75-83

This snippet returns the handle for PostgreSQL or MySQL:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-code-src_sql_kernel_qsqlresult.py
    :lines: 88-96

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDriver.handle`.
