.. sip:method-description::
    :status: todo
    :pysig: 546ade640b6edfbc8a086ef31347e768
    :realsig: () const
    :digest: ad66de5f90df1cfea5da990ef3144054

Returns the gamma level of the decoded image. If :sip:ref:`~PyQt5.QtGui.QImageReader.setGamma` has been called and gamma correction is supported it will return the gamma set. If gamma level is not supported by the image format, ``0.0`` is returned.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.setGamma`.
