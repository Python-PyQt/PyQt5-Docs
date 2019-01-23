.. sip:method-description::
    :status: todo
    :pysig: 546ade640b6edfbc8a086ef31347e768
    :realsig: (qreal)
    :digest: 935f1511e8bb2cc3751fde82c819feaf

Sets the denoising adjustment *level*.

Valid denoising values range between -1.0 and 1.0, with a default of 0.

If the parameter value is set to 0, the amount of denoising applied is selected by camera and depends on camera capabilities and settings. Changing value in -1.0..1.0 range adjusts the amount of denoising applied within the supported range.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QCameraImageProcessing.denoisingLevel`.
