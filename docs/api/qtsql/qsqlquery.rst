:orphan:

.. sip:class:: PyQt5.QtSql.QSqlQuery
    :description: QtSql/QSqlQuery-c.rst

    .. sip:enum:: PyQt5.QtSql.QSqlQuery.BatchExecutionMode
        :description: QtSql/QSqlQuery-BatchExecutionMode-e.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlQuery.BatchExecutionMode.ValuesAsColumns
            :description: QtSql/QSqlQuery-BatchExecutionMode-ValuesAsColumns-v.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlQuery.BatchExecutionMode.ValuesAsRows
            :description: QtSql/QSqlQuery-BatchExecutionMode-ValuesAsRows-v.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlResult`
        :description: QtSql/QSqlQuery-__init__-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlDatabase`
        :description: QtSql/QSqlQuery-__init__-f-1.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlQuery`
        :description: QtSql/QSqlQuery-__init__-f-2.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.__init__
        :args:
            query: str = ''
            db: :sip:ref:`~PyQt5.QtSql.QSqlDatabase` = QSqlDatabase()
        :description: QtSql/QSqlQuery-__init__-f-3.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.addBindValue
        :args:
            Any
            type: Union[:sip:ref:`~PyQt5.QtSql.QSql.ParamType`, :sip:ref:`~PyQt5.QtSql.QSql.ParamTypeFlag`] = :sip:ref:`~PyQt5.QtSql.QSql.ParamTypeFlag.In`
        :description: QtSql/QSqlQuery-addBindValue-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.at
        :returns:
            int
        :description: QtSql/QSqlQuery-at-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.bindValue
        :args:
            str
            Any
            type: Union[:sip:ref:`~PyQt5.QtSql.QSql.ParamType`, :sip:ref:`~PyQt5.QtSql.QSql.ParamTypeFlag`] = :sip:ref:`~PyQt5.QtSql.QSql.ParamTypeFlag.In`
        :description: QtSql/QSqlQuery-bindValue-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.bindValue
        :args:
            int
            Any
            type: Union[:sip:ref:`~PyQt5.QtSql.QSql.ParamType`, :sip:ref:`~PyQt5.QtSql.QSql.ParamTypeFlag`] = :sip:ref:`~PyQt5.QtSql.QSql.ParamTypeFlag.In`
        :description: QtSql/QSqlQuery-bindValue-f-1.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.boundValue
        :args:
            str
        :returns:
            Any
        :description: QtSql/QSqlQuery-boundValue-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.boundValue
        :args:
            int
        :returns:
            Any
        :description: QtSql/QSqlQuery-boundValue-f-1.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.boundValues
        :returns:
            Dict[str, Any]
        :description: QtSql/QSqlQuery-boundValues-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.clear
        :description: QtSql/QSqlQuery-clear-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.driver
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSqlDriver`
        :description: QtSql/QSqlQuery-driver-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.exec
        :returns:
            bool
        :description: QtSql/QSqlQuery-exec-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.exec
        :args:
            str
        :returns:
            bool
        :description: QtSql/QSqlQuery-exec-f-1.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.exec_
        :returns:
            bool
        :description: QtSql/QSqlQuery-exec_-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.exec_
        :args:
            str
        :returns:
            bool
        :description: QtSql/QSqlQuery-exec_-f-1.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.execBatch
        :args:
            mode: :sip:ref:`~PyQt5.QtSql.QSqlQuery.BatchExecutionMode` = :sip:ref:`~PyQt5.QtSql.QSqlQuery.BatchExecutionMode.ValuesAsRows`
        :returns:
            bool
        :description: QtSql/QSqlQuery-execBatch-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.executedQuery
        :returns:
            str
        :description: QtSql/QSqlQuery-executedQuery-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.finish
        :description: QtSql/QSqlQuery-finish-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.first
        :returns:
            bool
        :description: QtSql/QSqlQuery-first-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.isActive
        :returns:
            bool
        :description: QtSql/QSqlQuery-isActive-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.isForwardOnly
        :returns:
            bool
        :description: QtSql/QSqlQuery-isForwardOnly-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.isNull
        :args:
            int
        :returns:
            bool
        :description: QtSql/QSqlQuery-isNull-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.isNull
        :args:
            str
        :returns:
            bool
        :description: QtSql/QSqlQuery-isNull-f-1.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.isSelect
        :returns:
            bool
        :description: QtSql/QSqlQuery-isSelect-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.isValid
        :returns:
            bool
        :description: QtSql/QSqlQuery-isValid-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.last
        :returns:
            bool
        :description: QtSql/QSqlQuery-last-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.lastError
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSqlError`
        :description: QtSql/QSqlQuery-lastError-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.lastInsertId
        :returns:
            Any
        :description: QtSql/QSqlQuery-lastInsertId-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.lastQuery
        :returns:
            str
        :description: QtSql/QSqlQuery-lastQuery-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.next
        :returns:
            bool
        :description: QtSql/QSqlQuery-next-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.nextResult
        :returns:
            bool
        :description: QtSql/QSqlQuery-nextResult-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.numericalPrecisionPolicy
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSql.NumericalPrecisionPolicy`
        :description: QtSql/QSqlQuery-numericalPrecisionPolicy-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.numRowsAffected
        :returns:
            int
        :description: QtSql/QSqlQuery-numRowsAffected-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.prepare
        :args:
            str
        :returns:
            bool
        :description: QtSql/QSqlQuery-prepare-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.previous
        :returns:
            bool
        :description: QtSql/QSqlQuery-previous-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.record
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSqlRecord`
        :description: QtSql/QSqlQuery-record-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.result
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSqlResult`
        :description: QtSql/QSqlQuery-result-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.seek
        :args:
            int
            relative: bool = False
        :returns:
            bool
        :description: QtSql/QSqlQuery-seek-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.setForwardOnly
        :args:
            bool
        :description: QtSql/QSqlQuery-setForwardOnly-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.setNumericalPrecisionPolicy
        :args:
            :sip:ref:`~PyQt5.QtSql.QSql.NumericalPrecisionPolicy`
        :description: QtSql/QSqlQuery-setNumericalPrecisionPolicy-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.size
        :returns:
            int
        :description: QtSql/QSqlQuery-size-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.value
        :args:
            int
        :returns:
            Any
        :description: QtSql/QSqlQuery-value-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlQuery.value
        :args:
            str
        :returns:
            Any
        :description: QtSql/QSqlQuery-value-f-1.rst
