.. sip:method-description::
    :status: todo
    :pysig: f4b16e65d42ad609ac1af344eee47372
    :realsig: (const QByteArray&)
    :digest: 4c44244016fc3744faf9c383aeb6ac38

Sets the format :sip:ref:`~PyQt5.QtGui.QImageWriter` will use when writing images, to *format*. *format* is a case insensitive text string. Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qimagewriter.py
    :lines: 54-55

You can call :sip:ref:`~PyQt5.QtGui.QImageWriter.supportedImageFormats` for the full list of formats :sip:ref:`~PyQt5.QtGui.QImageWriter` supports.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageWriter.format`.
