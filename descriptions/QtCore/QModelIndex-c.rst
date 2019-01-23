.. sip:class-description::
    :status: todo
    :brief: Used to locate data in a data model
    :digest: 3af2631633134f70b490374cc6146a62

The :sip:ref:`~PyQt5.QtCore.QModelIndex` class is used to locate data in a data model.

This class is used as an index into item models derived from :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`. The index is used by item views, delegates, and selection models to locate an item in the model.

New :sip:ref:`~PyQt5.QtCore.QModelIndex` objects are created by the model using the :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.createIndex` function. An *invalid* model index can be constructed with the :sip:ref:`~PyQt5.QtCore.QModelIndex` constructor. Invalid indexes are often used as parent indexes when referring to top-level items in a model.

Model indexes refer to items in models, and contain all the information required to specify their locations in those models. Each index is located in a given row and column, and may have a parent index; use row(), column(), and  to obtain this information. Each top-level item in a model is represented by a model index that does not have a parent index - in this case,  will return an invalid model index, equivalent to an index constructed with the zero argument form of the :sip:ref:`~PyQt5.QtCore.QModelIndex` constructor.

To obtain a model index that refers to an existing item in a model, call :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.index` with the required row and column values, and the model index of the parent. When referring to top-level items in a model, supply :sip:ref:`~PyQt5.QtCore.QModelIndex` as the parent index.

The :sip:ref:`~PyQt5.QtCore.QModelIndex.model` function returns the model that the index references as a :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`. The  function is used to examine items held under the index in the model. The :sip:ref:`~PyQt5.QtCore.QModelIndex.sibling` function allows you to traverse items in the model on the same level as the index.

**Note:** Model indexes should be used immediately and then discarded. You should not rely on indexes to remain valid after calling model functions that change the structure of the model or delete items. If you need to keep a model index over time use a :sip:ref:`~PyQt5.QtCore.QPersistentModelIndex`.

.. seealso:: `Model/View Programming <https://doc.qt.io/qt-5/model-view-programming.html>`_, :sip:ref:`~PyQt5.QtCore.QPersistentModelIndex`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`.
