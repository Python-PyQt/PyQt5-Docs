.. sip:method-description::
    :status: todo
    :pysig: 546ade640b6edfbc8a086ef31347e768
    :realsig: (float)
    :digest: be6d31d613febe770a7333f3fdc03ad7

This is an image format specific function that sets the gamma level of the image to *gamma*. For image formats that do not support setting the gamma level, this value is ignored.

The value range of *gamma* depends on the image format. For example, the "png" format supports a gamma range from 0.0 to 1.0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageWriter.gamma`, :sip:ref:`~PyQt5.QtGui.QImageWriter.quality`.
