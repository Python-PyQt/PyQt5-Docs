.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: f2ac434a6ee36577c5e7ab45a96640f6

Sets the file name of :sip:ref:`~PyQt5.QtGui.QImageReader` to *fileName*. Internally, :sip:ref:`~PyQt5.QtGui.QImageReader` will create a :sip:ref:`~PyQt5.QtCore.QFile` object and open it in :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadOnly` mode, and use this when reading images.

If *fileName* does not include a file extension (e.g., .png or .bmp), :sip:ref:`~PyQt5.QtGui.QImageReader` will cycle through all supported extensions until it finds a matching file.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.fileName`, :sip:ref:`~PyQt5.QtGui.QImageReader.setDevice`, :sip:ref:`~PyQt5.QtGui.QImageReader.supportedImageFormats`.
