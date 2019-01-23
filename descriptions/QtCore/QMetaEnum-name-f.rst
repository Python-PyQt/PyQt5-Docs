.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: 074b28900249a91bb807739ff8185fb7

Returns the name of the type (without the scope).

For example, the :sip:ref:`~PyQt5.QtCore.Qt.Key` enumeration has ``Key`` as the type name and :sip:ref:`~PyQt5.QtCore.Qt` as the scope.

For flags this returns the name of the flag type, not the name of the enum type.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaEnum.isValid`, :sip:ref:`~PyQt5.QtCore.QMetaEnum.scope`.
