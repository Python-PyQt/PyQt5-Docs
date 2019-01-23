.. sip:method-description::
    :status: todo
    :pysig: 546ade640b6edfbc8a086ef31347e768
    :realsig: (float)
    :digest: 02ed4c8500777071abd43407f2fd2faf

Sets the gamma value at which the picture will be viewed to *gamma*. If the picture format stores a gamma value for which the picture is intended to be used, then this setting will be used to modify the picture. Setting to 0.0 will disable gamma correction (i.e. any specification in the file will be ignored).

The default value is 0.0.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPictureIO.gamma`.
