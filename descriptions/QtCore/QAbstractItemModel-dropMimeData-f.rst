.. sip:method-description::
    :status: todo
    :pysig: 239945ef568657131dd9fd68797d4173
    :realsig: (const QMimeData*,Qt::DropAction,int,int,const QModelIndex&)
    :digest: 53136e5bd1db9da428875cb573a0808f

Handles the *data* supplied by a drag and drop operation that ended with the given *action*.

Returns ``true`` if the data and action were handled by the model; otherwise returns ``false``.

The specified *row*, *column* and *parent* indicate the location of an item in the model where the operation ended. It is the responsibility of the model to complete the action at the correct location.

For instance, a drop action on an item in a QTreeView can result in new items either being inserted as children of the item specified by *row*, *column*, and *parent*, or as siblings of the item.

When *row* and *column* are -1 it means that the dropped data should be considered as dropped directly on *parent*. Usually this will mean appending the data as child items of *parent*. If *row* and *column* are greater than or equal zero, it means that the drop occurred just before the specified *row* and *column* in the specified *parent*.

The :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes` member is called to get the list of acceptable MIME types. This default implementation assumes the default implementation of :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes`, which returns a single default MIME type. If you reimplement :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.mimeTypes` in your custom model to return multiple MIME types, you must reimplement this function to make use of them.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.supportedDropActions`, :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.canDropMimeData`, `Using drag and drop with item views <https://doc.qt.io/qt-5/model-view-programming.html#using-drag-and-drop-with-item-views>`_.
