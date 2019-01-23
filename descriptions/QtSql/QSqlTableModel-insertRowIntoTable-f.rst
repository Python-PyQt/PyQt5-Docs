.. sip:method-description::
    :status: todo
    :pysig: f67bcede2061a4cfd788dc038c63c953
    :realsig: (const QSqlRecord&)
    :digest: 26727895b9b1354328fb35d438a7fc38

Inserts the values *values* into the currently active database table.

This is a low-level method that operates directly on the database and should not be called directly. Use insertRow() and :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setData` to insert values. The model will decide depending on its edit strategy when to modify the database.

Returns ``true`` if the values could be inserted, otherwise false. Error information can be retrieved with lastError().

.. seealso:: lastError(), insertRow(), :sip:ref:`~PyQt5.QtSql.QSqlTableModel.insertRows`.
