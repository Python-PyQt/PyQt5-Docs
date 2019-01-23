.. sip:method-description::
    :status: todo
    :pysig: b01cc37027678fc5ed1053ac37b1c6a1
    :realsig: (int,int)
    :digest: 36c6cbca8c4cc39c59e273424241dbf1

Removes the child item at (\ *row*, *column*) without deleting it, and returns a pointer to the item. If there was no child at the given location, then this function returns 0.

Note that this function, unlike :sip:ref:`~PyQt5.QtGui.QStandardItem.takeRow` and :sip:ref:`~PyQt5.QtGui.QStandardItem.takeColumn`, does not affect the dimensions of the child table.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItem.child`, :sip:ref:`~PyQt5.QtGui.QStandardItem.takeRow`, :sip:ref:`~PyQt5.QtGui.QStandardItem.takeColumn`.
