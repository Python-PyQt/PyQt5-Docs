.. sip:method-description::
    :status: todo
    :pysig: feacfd0c279f090da349566ddfccd0cf
    :realsig: (const QImage&,QClipboard::Mode)
    :digest: 02f558037d30adfec0945b2fcd511e77

Copies the *image* into the clipboard.

The *mode* argument is used to control which part of the system clipboard is used. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Clipboard`, the image is stored in the global clipboard. If *mode* is :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.Selection`, the data is stored in the global mouse selection.

This is shorthand for:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_kernel_qclipboard.py
    :lines: 62-64

.. seealso:: :sip:ref:`~PyQt5.QtGui.QClipboard.image`, :sip:ref:`~PyQt5.QtGui.QClipboard.setPixmap`, :sip:ref:`~PyQt5.QtGui.QClipboard.setMimeData`.
