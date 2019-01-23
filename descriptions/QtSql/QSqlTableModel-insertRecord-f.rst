.. sip:method-description::
    :status: todo
    :pysig: d20127397a4028c5952e5950ed383bc4
    :realsig: (int,const QSqlRecord&)
    :digest: 8554ea739b9837c69b71af5d54489b01

Inserts the *record* at position *row*. If *row* is negative, the record will be appended to the end. Calls :sip:ref:`~PyQt5.QtSql.QSqlTableModel.insertRows` and :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setRecord` internally.

Returns ``true`` if the record could be inserted, otherwise false.

Changes are submitted immediately for :sip:ref:`~PyQt5.QtSql.QSqlTableModel.EditStrategy.OnFieldChange` and :sip:ref:`~PyQt5.QtSql.QSqlTableModel.EditStrategy.OnRowChange`. Failure does not leave a new row in the model.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlTableModel.insertRows`, :sip:ref:`~PyQt5.QtSql.QSqlTableModel.removeRows`, :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setRecord`.
