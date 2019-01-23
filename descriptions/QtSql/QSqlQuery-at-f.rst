.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 5b91d1dcdbd258b727e5e0655cb30d9d

Returns the current internal position of the query. The first record is at position zero. If the position is invalid, the function returns QSql::BeforeFirstRow or QSql::AfterLastRow, which are special negative values.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlQuery.previous`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.next`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.first`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.last`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.seek`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.isActive`, :sip:ref:`~PyQt5.QtSql.QSqlQuery.isValid`.
