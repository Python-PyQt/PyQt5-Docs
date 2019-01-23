.. sip:method-description::
    :status: todo
    :pysig: 1c050147f1c6405ea95dfe40ab012b77
    :realsig: (const QSqlQuery&)
    :digest: 1c6d4142a8652ef0974346d158402d2a

This function simply calls :sip:ref:`~PyQt5.QtSql.QSqlQueryModel.setQuery`\ (\ *query*). You should normally not call it on a :sip:ref:`~PyQt5.QtSql.QSqlTableModel`. Instead, use :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setTable`, :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setSort`, :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setFilter`, etc., to set up the query.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlTableModel.selectStatement`.
