.. sip:method-description::
    :status: todo
    :pysig: 7c31cb71201a63ca3bf4a0b5c449f835
    :realsig: () const
    :digest: ca72f66ea65e62e5f17b18221f36de81

Returns the list of all available MIME types.

This can be useful for showing all MIME types to the user, for instance in a MIME type editor. Do not use unless really necessary in other cases though, prefer using the :sip:ref:`~PyQt5.QtCore.QMimeDatabase.mimeTypeForData` methods for performance reasons.
