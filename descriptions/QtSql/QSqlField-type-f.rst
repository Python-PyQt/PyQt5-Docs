.. sip:method-description::
    :status: todo
    :pysig: 7315aa43ae06953fab9deb476d0950e4
    :realsig: () const
    :digest: 6e9af0fe8d8a9bb43d20323a379b0c45

Returns the field's type as stored in the database. Note that the actual value might have a different type, Numerical values that are too large to store in a long int or double are usually stored as strings to prevent precision loss.

.. seealso:: :sip:ref:`~PyQt5.QtSql.QSqlField.setType`.
