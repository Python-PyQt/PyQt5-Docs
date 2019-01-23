.. sip:method-description::
    :status: todo
    :pysig: 02686623c57a80e2957e02cfef8f775a
    :realsig: () const
    :digest: 55de41ac47d8265b6dce4556e83b23b0

Returns a map of the bound values.

With named binding, the bound values can be examined in the following ways:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 214-219

With positional binding, the code becomes:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 226-228

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlQuery.boundValue`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.bindValue`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.addBindValue`.
