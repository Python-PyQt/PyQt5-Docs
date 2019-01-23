.. sip:method-description::
    :status: todo
    :pysig: 2cc8f0df6b41c199a0b762c15d9e2b16
    :realsig: (const QModelIndex&) const
    :digest: ecaeb3812ea6ee17d6f183915f554d64

Returns ``true`` if there is more data available for *parent*; otherwise returns ``false``.

The default implementation always returns ``false``.

If  returns ``true``, the :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.fetchMore` function should be called. This is the behavior of QAbstractItemView, for example.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractItemModel.fetchMore`.
