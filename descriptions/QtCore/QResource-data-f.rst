.. sip:method-description::
    :status: todo
    :pysig: 4b3a6218bb3e3a7303e8a171a60fcf92
    :realsig: () const
    :digest: ef2da47753400647062c2c69d22964f3

Returns direct access to a read only segment of data that this resource represents. If the resource is compressed the data returns is compressed and :sip:ref:`~PyQt5.QtCore.qUncompress` must be used to access the data. If the resource is a directory 0 is returned.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QResource.size`, :sip:ref:`~PyQt5.QtCore.QResource.isCompressed`, :sip:ref:`~PyQt5.QtCore.QResource.isFile`.
