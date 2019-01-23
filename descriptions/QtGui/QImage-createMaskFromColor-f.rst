.. sip:method-description::
    :status: todo
    :pysig: 0278059ca9e4a833acf2c2e2f95acfd0
    :realsig: (QRgb,Qt::MaskMode) const
    :digest: 49bb7be9f253208f5fb2842d9c67d173

Creates and returns a mask for this image based on the given *color* value. If the *mode* is MaskInColor (the default value), all pixels matching *color* will be opaque pixels in the mask. If *mode* is MaskOutColor, all pixels matching the given color will be transparent.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImage.createAlphaMask`, :sip:ref:`~PyQt5.QtGui.QImage.createHeuristicMask`.
