:orphan:

.. sip:class:: PyQt5.QtSql.QSqlError
    :description: QtSql/QSqlError-c.rst

    .. sip:enum:: PyQt5.QtSql.QSqlError.ErrorType
        :description: QtSql/QSqlError-ErrorType-e.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlError.ErrorType.ConnectionError
            :description: QtSql/QSqlError-ErrorType-ConnectionError-v.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlError.ErrorType.NoError
            :description: QtSql/QSqlError-ErrorType-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlError.ErrorType.StatementError
            :description: QtSql/QSqlError-ErrorType-StatementError-v.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlError.ErrorType.TransactionError
            :description: QtSql/QSqlError-ErrorType-TransactionError-v.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlError.ErrorType.UnknownError
            :description: QtSql/QSqlError-ErrorType-UnknownError-v.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.__init__
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlError`
        :description: QtSql/QSqlError-__init__-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.__init__
        :args:
            driverText: str = ''
            databaseText: str = ''
            type: :sip:ref:`~PyQt5.QtSql.QSqlError.ErrorType` = :sip:ref:`~PyQt5.QtSql.QSqlError.ErrorType.NoError`
            errorCode: str = ''
        :description: QtSql/QSqlError-__init__-f-1.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.__init__
        :args:
            str
            str
            :sip:ref:`~PyQt5.QtSql.QSqlError.ErrorType`
            int
        :description: QtSql/QSqlError-__init__-f-2.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.databaseText
        :returns:
            str
        :description: QtSql/QSqlError-databaseText-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.driverText
        :returns:
            str
        :description: QtSql/QSqlError-driverText-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.__eq__
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlError`
        :returns:
            bool
        :description: QtSql/QSqlError-__eq__-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.isValid
        :returns:
            bool
        :description: QtSql/QSqlError-isValid-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.nativeErrorCode
        :returns:
            str
        :description: QtSql/QSqlError-nativeErrorCode-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.__ne__
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlError`
        :returns:
            bool
        :description: QtSql/QSqlError-__ne__-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.number
        :returns:
            int
        :description: QtSql/QSqlError-number-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.setDatabaseText
        :args:
            str
        :description: QtSql/QSqlError-setDatabaseText-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.setDriverText
        :args:
            str
        :description: QtSql/QSqlError-setDriverText-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.setNumber
        :args:
            int
        :description: QtSql/QSqlError-setNumber-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.setType
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlError.ErrorType`
        :description: QtSql/QSqlError-setType-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.swap
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlError`
        :description: QtSql/QSqlError-swap-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.text
        :returns:
            str
        :description: QtSql/QSqlError-text-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlError.type
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSqlError.ErrorType`
        :description: QtSql/QSqlError-type-f.rst
