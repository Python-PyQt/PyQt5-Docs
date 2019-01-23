.. sip:method-description::
    :status: todo
    :pysig: ed7d36b2453c0ad34c94a4b835ead66e
    :realsig: (const QModelIndex&,QItemSelectionModel::SelectionFlags)
    :digest: 96d89e397ae720c5db6e76b350072de4

Sets the model item *index* to be the current item, and emits :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.currentChanged`. The current item is used for keyboard navigation and focus indication; it is independent of any selected items, although a selected item can also be the current item.

Depending on the specified *command*, the *index* can also become part of the current selection.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.currentIndex`, :sip:ref:`~PyQt5.QtCore.QItemSelectionModel.select`.
