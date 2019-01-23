.. sip:method-description::
    :status: todo
    :pysig: 546ade640b6edfbc8a086ef31347e768
    :realsig: (float)
    :digest: cf2afdcd6ddf77a5aef7266274c7943b

This is an image format specific function that forces images with gamma information to be gamma corrected to *gamma*. For image formats that do not support gamma correction, this value is ignored.

To gamma correct to a standard PC color-space, set gamma to ``1/2.2``.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.gamma`.
