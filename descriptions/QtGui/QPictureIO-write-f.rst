.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: ()
    :digest: 922bec1d1cf61220a45760ad3d57b795

Writes an picture to an IO device and returns ``true`` if the picture was successfully written; otherwise returns ``false``.

Before writing an picture you must set an IO device or a file name. If both an IO device and a file name have been set, the IO device will be used.

The picture will be written using the specified picture format.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-picture-picture.py
    :lines: 123-131

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPictureIO.setIODevice`, :sip:ref:`~PyQt5.QtGui.QPictureIO.setFileName`, :sip:ref:`~PyQt5.QtGui.QPictureIO.setFormat`, :sip:ref:`~PyQt5.QtGui.QPictureIO.read`, :sip:ref:`~PyQt5.QtGui.QPixmap.save`.
