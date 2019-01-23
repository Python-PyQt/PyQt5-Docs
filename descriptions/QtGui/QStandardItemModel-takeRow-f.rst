.. sip:method-description::
    :status: todo
    :pysig: 929c828b18d8f30c1df1986af20db4a6
    :realsig: (int)
    :digest: 90a1140eec925718b24870a94a5fa651

Removes the given *row* without deleting the row items, and returns a list of pointers to the removed items. The model releases ownership of the items. For items in the row that have not been set, the corresponding pointers in the list will be 0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItemModel.takeColumn`.
