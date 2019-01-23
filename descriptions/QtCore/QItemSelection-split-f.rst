.. sip:method-description::
    :status: todo
    :pysig: 2e76760c727bf5f9354fc95ffa638d45
    :realsig: (const QItemSelectionRange&,const QItemSelectionRange&,QItemSelection*)
    :digest: 7a021fd03043948e12f98ffa2c5dd741

Splits the selection *range* using the selection *other* range. Removes all items in *other* from *range* and puts the result in *result*. This can be compared with the semantics of the *subtract* operation of a set.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QItemSelection.merge`.
