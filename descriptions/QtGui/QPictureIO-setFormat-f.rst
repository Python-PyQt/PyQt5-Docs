.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const char*)
    :digest: 9d668099d6dce082dd9ccab69c703b1f

Sets the picture format to *format* for the picture to be read or written.

It is necessary to specify a format before writing an picture, but it is not necessary to specify a format before reading an picture.

If no format has been set, Qt guesses the picture format before reading it. If a format is set the picture will only be read if it has that format.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPictureIO.read`, :sip:ref:`~PyQt5.QtGui.QPictureIO.write`, :sip:ref:`~PyQt5.QtGui.QPictureIO.format`.
