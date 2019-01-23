.. sip:method-description::
    :status: todo
    :pysig: 929c828b18d8f30c1df1986af20db4a6
    :realsig: (int)
    :digest: 19b123eab6250f9de1d858c8e4e8cdb7

Removes the given *column* without deleting the column items, and returns a list of pointers to the removed items. The model releases ownership of the items. For items in the column that have not been set, the corresponding pointers in the list will be 0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItemModel.takeRow`.
