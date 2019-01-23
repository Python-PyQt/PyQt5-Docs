.. sip:class-description::
    :status: todo
    :brief: Manages information about a range of selected items in a model
    :digest: 199121096182df2e653b257cc7ad9cf2

The :sip:ref:`~PyQt5.QtCore.QItemSelectionRange` class manages information about a range of selected items in a model.

A :sip:ref:`~PyQt5.QtCore.QItemSelectionRange` contains information about a range of selected items in a model. A range of items is a contiguous array of model items, extending to cover a number of adjacent rows and columns with a common parent item; this can be visualized as a two-dimensional block of cells in a table. A selection range has a top(), :sip:ref:`~PyQt5.QtCore.left` a bottom(), :sip:ref:`~PyQt5.QtCore.right` and a .

The :sip:ref:`~PyQt5.QtCore.QItemSelectionRange` class is one of the `Model/View Classes <https://doc.qt.io/qt-5/model-view-programming.html#model-view-classes>`_ and is part of Qt's `model/view framework <https://doc.qt.io/qt-5/model-view-programming.html>`_.

The model items contained in the selection range can be obtained using the :sip:ref:`~PyQt5.QtCore.QItemSelectionRange.indexes` function. Use :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.selectedIndexes` to get a list of all selected items for a view.

You can determine whether a given model item lies within a particular range by using the  function. Ranges can also be compared using the overloaded operators for equality and inequality, and the intersects() function allows you to determine whether two ranges overlap.

.. seealso:: `Model/View Programming <https://doc.qt.io/qt-5/model-view-programming.html>`_, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`, :sip:ref:`~PyQt5.QtCore.QItemSelection`, :sip:ref:`~PyQt5.QtCore.QItemSelectionModel`.
