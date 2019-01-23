.. sip:method-description::
    :status: todo
    :pysig: 929c828b18d8f30c1df1986af20db4a6
    :realsig: (int)
    :digest: 5cd20bf7abbb4fbfd04446bf2de2a41d

Removes *row* without deleting the row items, and returns a list of pointers to the removed items. For items in the row that have not been set, the corresponding pointers in the list will be 0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItem.removeRow`, :sip:ref:`~PyQt5.QtGui.QStandardItem.insertRow`, :sip:ref:`~PyQt5.QtGui.QStandardItem.takeColumn`.
