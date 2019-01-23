.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: 3888fc3e5050a50c26dd2881c79489db

Sets the IO device to be used for reading or writing an picture.

Setting the IO device allows pictures to be read/written to any block-oriented :sip:ref:`~PyQt5.QtCore.QIODevice`.

If *ioDevice* is not null, this IO device will override file name settings.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPictureIO.setFileName`.
