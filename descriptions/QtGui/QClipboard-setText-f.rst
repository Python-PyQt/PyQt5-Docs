.. sip:method-description::
    :status: todo
    :pysig: 9953a74262a726a378439ac674e9ac03
    :realsig: (const QString&,QClipboard::Mode)
    :digest: dfcccdba8426d588a464feaceff51d32

Copies *text* into the clipboard as plain text.

The *mode* argument is used to control which part of the system clipboard is used. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Clipboard`, the text is stored in the global clipboard. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Selection`, the text is stored in the global mouse selection. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.FindBuffer`, the text is stored in the search string buffer.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QClipboard.text`, :sip:ref:`~PyQt5.QtGui.QClipboard.setMimeData`.
