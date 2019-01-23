.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: 68138ccc739a687271b15decd9707b61

Sets the quality of the written picture to *q*, related to the compression ratio.

*q* must be in the range -1..100. Specify 0 to obtain small compressed files, 100 for large uncompressed files. (-1 signifies the default compression.)

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPictureIO.quality`, :sip:ref:`~PyQt5.QtGui.QPicture.save`.
