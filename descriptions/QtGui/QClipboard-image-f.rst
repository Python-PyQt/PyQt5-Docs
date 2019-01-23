.. sip:method-description::
    :status: todo
    :pysig: b5a41eb31b21125b06357c1596a65890
    :realsig: (QClipboard::Mode) const
    :digest: 6feee8a8e025a88c18d1c49093f1474c

Returns the clipboard image, or returns a null image if the clipboard does not contain an image or if it contains an image in an unsupported image format.

The *mode* argument is used to control which part of the system clipboard is used. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Clipboard`, the image is retrieved from the global clipboard. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Selection`, the image is retrieved from the global mouse selection.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QClipboard.setImage`, :sip:ref:`~PyQt5.QtGui.QClipboard.pixmap`, :sip:ref:`~PyQt5.QtGui.QClipboard.mimeData`.
