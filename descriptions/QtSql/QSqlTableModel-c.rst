.. sip:class-description::
    :status: todo
    :brief: Editable data model for a single database table
    :digest: b4ffff5e424491d0f9cd782c4158b766

The :sip:ref:`~PyQt5.QtSql.QSqlTableModel` class provides an editable data model for a single database table.

:sip:ref:`~PyQt5.QtSql.QSqlTableModel` is a high-level interface for reading and writing database records from a single table. It is built on top of the lower-level :sip:ref:`~PyQt5.QtSql.QSqlQuery` and can be used to provide data to view classes such as QTableView. For example:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 296-306

We set the SQL table's name and the edit strategy, then we set up the labels displayed in the view header. The edit strategy dictates when the changes done by the user in the view are actually applied to the database. The possible values are :sip:ref:`~PyQt5.QtSql.QSqlTableModel.EditStrategy.OnFieldChange`, :sip:ref:`~PyQt5.QtSql.QSqlTableModel.EditStrategy.OnRowChange`, and :sip:ref:`~PyQt5.QtSql.QSqlTableModel.EditStrategy.OnManualSubmit`.

:sip:ref:`~PyQt5.QtSql.QSqlTableModel` can also be used to access a database programmatically, without binding it to a view:

.. literalinclude:: ../../../snippets/qtbase-src-sql-doc-snippets-sqldatabase-sqldatabase.py
    :lines: 254-257

The code snippet above extracts the ``salary`` field from record 4 in the result set of the query ``SELECT \* from employee``.

It is possible to set filters using :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setFilter`, or modify the sort order using :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setSort`. At the end, you must call :sip:ref:`~PyQt5.QtSql.QSqlTableModel.select` to populate the model with data.

The `tablemodel <https://doc.qt.io/qt-5/qtsql-tablemodel-example.html>`_ example illustrates how to use :sip:ref:`~PyQt5.QtSql.QSqlTableModel` as the data source for a QTableView.

:sip:ref:`~PyQt5.QtSql.QSqlTableModel` provides no direct support for foreign keys. Use the :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel` and QSqlRelationalDelegate if you want to resolve foreign keys.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel`, :sip:ref:`~PyQt5.QtSql.QSqlQuery`, `Model/View Programming <https://doc.qt.io/qt-5/model-view-programming.html>`_, `Table Model Example <https://doc.qt.io/qt-5/qtsql-tablemodel-example.html>`_, `Cached Table Example <https://doc.qt.io/qt-5/qtsql-cachedtable-example.html>`_.
