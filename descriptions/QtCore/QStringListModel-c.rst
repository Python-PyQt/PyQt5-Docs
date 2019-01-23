.. sip:class-description::
    :status: todo
    :brief: Model that supplies strings to views
    :digest: 87f674f140a87ad30cb5f5336f6393b9

The :sip:ref:`~PyQt5.QtCore.QStringListModel` class provides a model that supplies strings to views.

:sip:ref:`~PyQt5.QtCore.QStringListModel` is an editable model that can be used for simple cases where you need to display a number of strings in a view widget, such as a QListView or a QComboBox.

The model provides all the standard functions of an editable model, representing the data in the string list as a model with one column and a number of rows equal to the number of items in the list.

Model indexes corresponding to items are obtained with the :sip:ref:`~PyQt5.QtCore.QAbstractListModel.index` function, and item flags are obtained with :sip:ref:`~PyQt5.QtCore.QStringListModel.flags`. Item data is read with the :sip:ref:`~PyQt5.QtCore.QStringListModel.data` function and written with :sip:ref:`~PyQt5.QtCore.QStringListModel.setData`. The number of rows (and number of items in the string list) can be found with the :sip:ref:`~PyQt5.QtCore.QStringListModel.rowCount` function.

The model can be constructed with an existing string list, or strings can be set later with the :sip:ref:`~PyQt5.QtCore.QStringListModel.setStringList` convenience function. Strings can also be inserted in the usual way with the :sip:ref:`~PyQt5.QtCore.QStringListModel.insertRows` function, and removed with :sip:ref:`~PyQt5.QtCore.QStringListModel.removeRows`. The contents of the string list can be retrieved with the :sip:ref:`~PyQt5.QtCore.QStringListModel.stringList` convenience function.

An example usage of :sip:ref:`~PyQt5.QtCore.QStringListModel`:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qstringlistmodel-main.py
    :lines: 65-68

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractListModel`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`, `Model Classes <https://doc.qt.io/qt-5/model-view-programming.html#model-classes>`_.
