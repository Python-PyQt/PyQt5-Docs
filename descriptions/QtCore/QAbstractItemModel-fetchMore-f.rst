.. sip:method-description::
    :status: todo
    :pysig: 2d99125b2256d2b6c1325ed8ea79240a
    :realsig: (const QModelIndex&)
    :digest: d740d5093ac83ca42a52711a0193747b

Fetches any available data for the items with the parent specified by the *parent* index.

Reimplement this if you are populating your model incrementally.

The default implementation does nothing.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.canFetchMore`.
