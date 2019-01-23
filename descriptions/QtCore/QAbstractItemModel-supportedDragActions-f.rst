.. sip:method-description::
    :status: todo
    :pysig: a7f4af82723099d0cfe336eff58e4905
    :realsig: () const
    :digest: 34468a4815b936a84d1071d1f3304ce0

Returns the actions supported by the data in this model.

The default implementation returns :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.supportedDropActions`. Reimplement this function if you wish to support additional actions.

is used by QAbstractItemView::startDrag() as the default values when a drag occurs.

.. seealso:: Qt::DropActions, `Using drag and drop with item views <https://doc.qt.io/qt-5/model-view-programming.html#using-drag-and-drop-with-item-views>`_.
