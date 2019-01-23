.. sip:method-description::
    :status: todo
    :pysig: 929c828b18d8f30c1df1986af20db4a6
    :realsig: (int)
    :digest: 3c300379444c9f9c6a90b7b4b5204552

Removes *column* without deleting the column items, and returns a list of pointers to the removed items. For items in the column that have not been set, the corresponding pointers in the list will be 0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItem.removeColumn`, :sip:ref:`~PyQt5.QtGui.QStandardItem.insertColumn`, :sip:ref:`~PyQt5.QtGui.QStandardItem.takeRow`.
