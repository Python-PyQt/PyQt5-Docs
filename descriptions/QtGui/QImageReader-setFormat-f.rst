.. sip:method-description::
    :status: todo
    :pysig: f4b16e65d42ad609ac1af344eee47372
    :realsig: (const QByteArray&)
    :digest: 30addf904b0e04b058af9aed1e191cba

Sets the format :sip:ref:`~PyQt5.QtGui.QImageReader` will use when reading images, to *format*. *format* is a case insensitive text string. Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qimagereader.py
    :lines: 54-55

You can call :sip:ref:`~PyQt5.QtGui.QImageReader.supportedImageFormats` for the full list of formats :sip:ref:`~PyQt5.QtGui.QImageReader` supports.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.format`.
