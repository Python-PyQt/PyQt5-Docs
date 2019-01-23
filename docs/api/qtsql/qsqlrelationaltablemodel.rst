:orphan:

.. sip:class:: PyQt5.QtSql.QSqlRelationalTableModel
    :inherits: :sip:ref:`~PyQt5.QtSql.QSqlTableModel`
    :description: QtSql/QSqlRelationalTableModel-c.rst

    .. sip:enum:: PyQt5.QtSql.QSqlRelationalTableModel.JoinMode
        :description: QtSql/QSqlRelationalTableModel-JoinMode-e.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlRelationalTableModel.JoinMode.InnerJoin
            :description: QtSql/QSqlRelationalTableModel-JoinMode-InnerJoin-v.rst

        .. sip:enum-member:: PyQt5.QtSql.QSqlRelationalTableModel.JoinMode.LeftJoin
            :description: QtSql/QSqlRelationalTableModel-JoinMode-LeftJoin-v.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
            db: :sip:ref:`~PyQt5.QtSql.QSqlDatabase` = QSqlDatabase()
        :description: QtSql/QSqlRelationalTableModel-__init__-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.clear
        :description: QtSql/QSqlRelationalTableModel-clear-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.data
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.DisplayRole`
        :returns:
            Any
        :description: QtSql/QSqlRelationalTableModel-data-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.insertRowIntoTable
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlRecord`
        :returns:
            bool
        :description: QtSql/QSqlRelationalTableModel-insertRowIntoTable-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.orderByClause
        :returns:
            str
        :description: QtSql/QSqlRelationalTableModel-orderByClause-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.relation
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSqlRelation`
        :description: QtSql/QSqlRelationalTableModel-relation-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.relationModel
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtSql.QSqlTableModel`
        :description: QtSql/QSqlRelationalTableModel-relationModel-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.removeColumns
        :args:
            int
            int
            parent: :sip:ref:`~PyQt5.QtCore.QModelIndex` = QModelIndex()
        :returns:
            bool
        :description: QtSql/QSqlRelationalTableModel-removeColumns-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.revertRow
        :args:
            int
        :description: QtSql/QSqlRelationalTableModel-revertRow-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.select
        :returns:
            bool
        :description: QtSql/QSqlRelationalTableModel-select-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.selectStatement
        :returns:
            str
        :description: QtSql/QSqlRelationalTableModel-selectStatement-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.setData
        :args:
            :sip:ref:`~PyQt5.QtCore.QModelIndex`
            Any
            role: int = :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.EditRole`
        :returns:
            bool
        :description: QtSql/QSqlRelationalTableModel-setData-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.setJoinMode
        :args:
            :sip:ref:`~PyQt5.QtSql.QSqlRelationalTableModel.JoinMode`
        :description: QtSql/QSqlRelationalTableModel-setJoinMode-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.setRelation
        :args:
            int
            :sip:ref:`~PyQt5.QtSql.QSqlRelation`
        :description: QtSql/QSqlRelationalTableModel-setRelation-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.setTable
        :args:
            str
        :description: QtSql/QSqlRelationalTableModel-setTable-f.rst

    .. sip:method:: PyQt5.QtSql.QSqlRelationalTableModel.updateRowInTable
        :args:
            int
            :sip:ref:`~PyQt5.QtSql.QSqlRecord`
        :returns:
            bool
        :description: QtSql/QSqlRelationalTableModel-updateRowInTable-f.rst
