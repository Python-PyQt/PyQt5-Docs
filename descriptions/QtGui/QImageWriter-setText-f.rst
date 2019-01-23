.. sip:method-description::
    :status: todo
    :pysig: 4b99ff73a8a869319570237b5c57ab03
    :realsig: (const QString&,const QString&)
    :digest: 0586ca76afec1b552336a601c7e1b174

Sets the image text associated with the key *key* to *text*. This is useful for storing copyright information or other information about the image. Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qimagewriter.py
    :lines: 60-63

If you want to store a single block of data (e.g., a comment), you can pass an empty key, or use a generic key like "Description".

The key and text will be embedded into the image data after calling :sip:ref:`~PyQt5.QtGui.QImageWriter.write`.

Support for this option is implemented through :sip:ref:`~PyQt5.QtGui.QImageIOHandler.ImageOption.Description`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.text`, :sip:ref:`~PyQt5.QtGui.QImage.setText`.
