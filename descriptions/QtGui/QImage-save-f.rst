.. sip:method-description::
    :status: todo
    :pysig: 18b89e220eebe5c40dbede2d92935137
    :realsig: (const QString&,const char*,int) const
    :digest: d6ff5f7a6cb46009824f85019a871f98

Saves the image to the file with the given *fileName*, using the given image file *format* and *quality* factor. If *format* is 0, :sip:ref:`~PyQt5.QtGui.QImage` will attempt to guess the format by looking at *fileName*'s suffix.

The *quality* factor must be in the range 0 to 100 or -1. Specify 0 to obtain small compressed files, 100 for large uncompressed files, and -1 (the default) to use the default settings.

Returns ``true`` if the image was successfully saved; otherwise returns ``false``.

.. seealso:: Reading and Writing Image Files.
