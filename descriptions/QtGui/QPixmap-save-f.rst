.. sip:method-description::
    :status: todo
    :pysig: 18b89e220eebe5c40dbede2d92935137
    :realsig: (const QString&,const char*,int) const
    :digest: 6b9143e48a2fcdf1b342b4732d5b01c2

Saves the pixmap to the file with the given *fileName* using the specified image file *format* and *quality* factor. Returns ``true`` if successful; otherwise returns ``false``.

The *quality* factor must be in the range [0,100] or -1. Specify 0 to obtain small compressed files, 100 for large uncompressed files, and -1 to use the default settings.

If *format* is 0, an image format will be chosen from *fileName*'s suffix.

.. seealso:: Reading and Writing Image Files.
