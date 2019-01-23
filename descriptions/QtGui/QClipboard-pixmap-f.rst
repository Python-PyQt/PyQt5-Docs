.. sip:method-description::
    :status: todo
    :pysig: f59629a3229bdf7b3dcf3e2c96b02f8d
    :realsig: (QClipboard::Mode) const
    :digest: 5ccdb9e2a8496ec10b4a387bf2d231cb

Returns the clipboard pixmap, or null if the clipboard does not contain a pixmap. Note that this can lose information. For example, if the image is 24-bit and the display is 8-bit, the result is converted to 8 bits, and if the image has an alpha channel, the result just has a mask.

The *mode* argument is used to control which part of the system clipboard is used. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Clipboard`, the pixmap is retrieved from the global clipboard. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Selection`, the pixmap is retrieved from the global mouse selection.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QClipboard.setPixmap`, :sip:ref:`~PyQt5.QtGui.QClipboard.image`, :sip:ref:`~PyQt5.QtGui.QClipboard.mimeData`, :sip:ref:`~PyQt5.QtGui.QPixmap.convertFromImage`.
