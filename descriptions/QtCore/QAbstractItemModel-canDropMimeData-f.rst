.. sip:method-description::
    :status: todo
    :pysig: 239945ef568657131dd9fd68797d4173
    :realsig: (const QMimeData*,Qt::DropAction,int,int,const QModelIndex&) const
    :digest: 591dba24896c6dcb6943efde087c6d5a

Returns ``true`` if a model can accept a drop of the *data*. This default implementation only checks if *data* has at least one format in the list of :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes` and if *action* is among the model's :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.supportedDropActions`.

Reimplement this function in your custom model, if you want to test whether the *data* can be dropped at *row*, *column*, *parent* with *action*. If you don't need that test, it is not necessary to reimplement this function.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.dropMimeData`, `Using drag and drop with item views <https://doc.qt.io/qt-5/model-view-programming.html#using-drag-and-drop-with-item-views>`_.
