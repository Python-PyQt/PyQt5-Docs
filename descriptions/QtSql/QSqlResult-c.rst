.. sip:class-description::
    :status: todo
    :brief: Abstract interface for accessing data from specific SQL databases
    :digest: 2501cf39bc9aea135b781b661a1b79f8

The :sip:ref:`~PyQt5.QtSql.QSqlResult` class provides an abstract interface for accessing data from specific SQL databases.

Normally, you would use :sip:ref:`~PyQt5.QtSql.QSqlQuery` instead of :sip:ref:`~PyQt5.QtSql.QSqlResult`, since :sip:ref:`~PyQt5.QtSql.QSqlQuery` provides a generic wrapper for database-specific implementations of :sip:ref:`~PyQt5.QtSql.QSqlResult`.

If you are implementing your own SQL driver (by subclassing :sip:ref:`~PyQt5.QtSql.QSqlDriver`), you will need to provide your own :sip:ref:`~PyQt5.QtSql.QSqlResult` subclass that implements all the pure virtual functions and other virtual functions that you need.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlDriver`.
