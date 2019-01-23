.. sip:method-description::
    :status: todo
    :pysig: cd6cc1b08f5862bb9d8e82048e789cf1
    :realsig: (QObject*,const QVariant&) const
    :digest: 8d8f1b607229c79808e10dda734fbd06

Writes *value* as the property's value to the given *object*. Returns true if the write succeeded; otherwise returns ``false``.

If *value* is not of the same type type as the property, a conversion is attempted. An empty QVariant() is equivalent to a call to :sip:ref:`~PyQt5.QtCore.reset` if this property is resetable, or setting a default-constructed object otherwise.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaProperty.read`, :sip:ref:`~PyQt5.QtCore.reset`, :sip:ref:`~PyQt5.QtCore.QMetaProperty.isWritable`.
