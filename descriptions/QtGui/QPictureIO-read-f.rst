.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: ()
    :digest: d21a269db3ea936ad914c8ed686e25a3

Reads an picture into memory and returns ``true`` if the picture was successfully read; otherwise returns ``false``.

Before reading an picture you must set an IO device or a file name. If both an IO device and a file name have been set, the IO device will be used.

Setting the picture file format string is optional.

Note that this function does *not* set the :sip:ref:`~PyQt5.QtGui.QPictureIO.format` used to read the picture. If you need that information, use the :sip:ref:`~PyQt5.QtGui.QPictureIO.pictureFormat` static functions.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-picture-picture.py
    :lines: 108-115

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPictureIO.setIODevice`, :sip:ref:`~PyQt5.QtGui.QPictureIO.setFileName`, :sip:ref:`~PyQt5.QtGui.QPictureIO.setFormat`, :sip:ref:`~PyQt5.QtGui.QPictureIO.write`, :sip:ref:`~PyQt5.QtGui.QPixmap.load`.
