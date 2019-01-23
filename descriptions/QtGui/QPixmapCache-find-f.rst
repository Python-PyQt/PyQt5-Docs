.. sip:method-description::
    :status: todo
    :pysig: 64e8559db0c61680ba437ddab8cd0d1b
    :realsig: (const QString&)
    :digest: 3193e3131db02e9dc49dbd26fb50148f

This is an overloaded function.

Returns the pixmap associated with the *key* in the cache, or null if there is no such pixmap.

**Warning:** If valid, you should copy the pixmap immediately (this is fast). Subsequent insertions into the cache could cause the pointer to become invalid. For this reason, we recommend you use bool find(const QString&, :sip:ref:`~PyQt5.QtGui.QPixmap`\*) instead.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qpixmapcache.py
    :lines: 54-62
