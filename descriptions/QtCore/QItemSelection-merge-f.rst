.. sip:method-description::
    :status: todo
    :pysig: 0ccd5d569a8e4ed61adb6d3777baa087
    :realsig: (const QItemSelection&,QItemSelectionModel::SelectionFlags)
    :digest: 3e8d3d61b57d3bfcb4178c13651e1aab

Merges the *other* selection with this :sip:ref:`~PyQt5.QtCore.QItemSelection` using the *command* given. This method guarantees that no ranges are overlapping.

Note that only :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlag.Select`, :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlag.Deselect`, and :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.SelectionFlag.Toggle` are supported.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QItemSelection.split`.
