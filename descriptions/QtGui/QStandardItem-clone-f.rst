.. sip:method-description::
    :status: todo
    :pysig: b777c3534b3f226a8adb441263c8e63c
    :realsig: () const
    :digest: efb7566ffde4f70f50da96220edcdb5a

Returns a copy of this item. The item's children are not copied.

When subclassing :sip:ref:`~PyQt5.QtGui.QStandardItem`, you can reimplement this function to provide :sip:ref:`~PyQt5.QtGui.QStandardItemModel` with a factory that it can use to create new items on demand.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItemModel.setItemPrototype`, operator=().
