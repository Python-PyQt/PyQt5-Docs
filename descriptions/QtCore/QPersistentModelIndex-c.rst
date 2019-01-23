.. sip:class-description::
    :status: todo
    :brief: Used to locate data in a data model
    :digest: d9bd2361039dcb77b3e44281ee63bc92

The :sip:ref:`~PyQt5.QtCore.QPersistentModelIndex` class is used to locate data in a data model.

A :sip:ref:`~PyQt5.QtCore.QPersistentModelIndex` is a model index that can be stored by an application, and later used to access information in a model. Unlike the :sip:ref:`~PyQt5.QtCore.QModelIndex` class, it is safe to store a :sip:ref:`~PyQt5.QtCore.QPersistentModelIndex` since the model will ensure that references to items will continue to be valid as long as they can be accessed by the model.

It is good practice to check that persistent model indexes are valid before using them.

.. seealso:: `Model/View Programming <https://doc.qt.io/qt-5/model-view-programming.html>`_, :sip:ref:`~PyQt5.QtCore.QModelIndex`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`.
