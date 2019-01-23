.. sip:method-description::
    :status: todo
    :pysig: 6359afdf86b9ec14316ea3f79e266b65
    :realsig: () const
    :digest: 11fc022c5941d1ceeda902033fe42c36

Returns the format :sip:ref:`~PyQt5.QtGui.QImageReader` uses for reading images.

You can call this function after assigning a device to the reader to determine the format of the device. For example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qimagereader.py
    :lines: 60-61

If the reader cannot read any image from the device (e.g., there is no image there, or the image has already been read), or if the format is unsupported, this function returns an empty QByteArray().

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.setFormat`, :sip:ref:`~PyQt5.QtGui.QImageReader.supportedImageFormats`.
