.. sip:method-description::
    :status: todo
    :pysig: d20127397a4028c5952e5950ed383bc4
    :realsig: (int,const QSqlRecord&)
    :digest: 9352125a15fdb466694e741e80580d75

Updates the given *row* in the currently active database table with the specified *values*. Returns ``true`` if successful; otherwise returns ``false``.

This is a low-level method that operates directly on the database and should not be called directly. Use :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setData` to update values. The model will decide depending on its edit strategy when to modify the database.

Note that only values that have the generated-flag set are updated. The generated-flag can be set with :sip:ref:`~PyQt5.QtSql.QSqlRecord.setGenerated` and tested with :sip:ref:`~PyQt5.QtSql.QSqlRecord.isGenerated`.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlRecord.isGenerated`, :sip:ref:`~PyQt5.QtSql.QSqlTableModel.setData`.
