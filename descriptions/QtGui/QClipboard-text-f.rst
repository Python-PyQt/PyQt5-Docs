.. sip:method-description::
    :status: todo
    :pysig: f239deb0b43ce7c5f050be06c83df045
    :realsig: (QClipboard::Mode) const
    :digest: 873f78fb74ee232389ed5d8af6cee243

Returns the clipboard text as plain text, or an empty string if the clipboard does not contain any text.

The *mode* argument is used to control which part of the system clipboard is used. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Clipboard`, the text is retrieved from the global clipboard. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Selection`, the text is retrieved from the global mouse selection. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.FindBuffer`, the text is retrieved from the search string buffer.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QClipboard.setText`, :sip:ref:`~PyQt5.QtGui.QClipboard.mimeData`.
