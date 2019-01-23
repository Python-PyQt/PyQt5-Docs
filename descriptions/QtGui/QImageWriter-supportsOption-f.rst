.. sip:method-description::
    :status: todo
    :pysig: 3c2e46f39ae57839c31bc1198c8fcde8
    :realsig: (QImageIOHandler::ImageOption) const
    :digest: e427d2a324bbe37311f291ecfc8c4e1c

Returns ``true`` if the writer supports *option*; otherwise returns false.

Different image formats support different options. Call this function to determine whether a certain option is supported by the current format. For example, the PNG format allows you to embed text into the image's metadata (see text()).

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qimagewriter.py
    :lines: 68-70

Options can be tested after the writer has been associated with a format.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.supportsOption`, :sip:ref:`~PyQt5.QtGui.QImageWriter.setFormat`.
