.. sip:method-description::
    :status: todo
    :pysig: 532b8651bdbedbf2c94c374363ccb539
    :realsig: (const QPixmap&,QClipboard::Mode)
    :digest: 6c9b8c616c97fa30291d756e5a650463

Copies *pixmap* into the clipboard. Note that this is slower than :sip:ref:`~PyQt5.QtGui.QClipboard.setImage` because it needs to convert the :sip:ref:`~PyQt5.QtGui.QPixmap` to a :sip:ref:`~PyQt5.QtGui.QImage` first.

The *mode* argument is used to control which part of the system clipboard is used. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Clipboard`, the pixmap is stored in the global clipboard. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Selection`, the pixmap is stored in the global mouse selection.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QClipboard.pixmap`, :sip:ref:`~PyQt5.QtGui.QClipboard.setImage`, :sip:ref:`~PyQt5.QtGui.QClipboard.setMimeData`.
