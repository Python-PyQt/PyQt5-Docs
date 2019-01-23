.. sip:class-description::
    :status: todo
    :brief: Read-only data model for SQL result sets
    :digest: 40af653d88a06fba581f769a1e401965

The :sip:ref:`~PyQt5.QtSql.QSqlQueryModel` class provides a read-only data model for SQL result sets.

:sip:ref:`~PyQt5.QtSql.QSqlQueryModel` is a high-level interface for executing SQL statements and traversing the result set. It is built on top of the lower-level :sip:ref:`~PyQt5.QtSql.QSqlQuery` and can be used to provide data to view classes such as QTableView. For example:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 237-247

We set the model's query, then we set up the labels displayed in the view header.

:sip:ref:`~PyQt5.QtSql.QSqlQueryModel` can also be used to access a database programmatically, without binding it to a view:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 254-257

The code snippet above extracts the ``salary`` field from record 4 in the result set of the query ``SELECT \* from employee``. Assuming that ``salary`` is column 2, we can rewrite the last line as follows:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 263-263

The model is read-only by default. To make it read-write, you must subclass it and reimplement setData() and flags(). Another option is to use :sip:ref:`~PyQt5.QtSql.QSqlTableModel`, which provides a read-write model based on a single database table.

The `querymodel <https://doc.qt.io/qt-5/qtsql-querymodel-example.html>`_ example illustrates how to use :sip:ref:`~PyQt5.QtSql.QSqlQueryModel` to display the result of a query. It also shows how to subclass :sip:ref:`~PyQt5.QtSql.QSqlQueryModel` to customize the contents of the data before showing it to the user, and how to create a read-write model based on :sip:ref:`~PyQt5.QtSql.QSqlQueryModel`.

If the database doesn't return the number of selected rows in a query, the model will fetch rows incrementally. See :sip:ref:`~PyQt5.QtSql.QSqlQueryModel.fetchMore` for more information.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlTableModel`, :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel`, :sip:ref:`~PyQt5.QtSql.QSqlQuery`, `Model/View Programming <https://doc.qt.io/qt-5/model-view-programming.html>`_, `Query Model Example <https://doc.qt.io/qt-5/qtsql-querymodel-example.html>`_.
