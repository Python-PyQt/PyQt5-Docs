.. sip:method-description::
    :status: todo
    :pysig: b777c3534b3f226a8adb441263c8e63c
    :realsig: (const QStandardItem*)
    :digest: 1627d1a9df5375e17bfb74d571a4626f

Sets the item prototype for the model to the specified *item*. The model takes ownership of the prototype.

The item prototype acts as a :sip:ref:`~PyQt5.QtGui.QStandardItem` factory, by relying on the :sip:ref:`~PyQt5.QtGui.QStandardItem.clone` function. To provide your own prototype, subclass :sip:ref:`~PyQt5.QtGui.QStandardItem`, reimplement :sip:ref:`~PyQt5.QtGui.QStandardItem.clone` and set the prototype to be an instance of your custom class. Whenever :sip:ref:`~PyQt5.QtGui.QStandardItemModel` needs to create an item on demand (for instance, when a view or item delegate calls :sip:ref:`~PyQt5.QtGui.QStandardItemModel.setData`)), the new items will be instances of your custom class.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStandardItemModel.itemPrototype`, :sip:ref:`~PyQt5.QtGui.QStandardItem.clone`.
