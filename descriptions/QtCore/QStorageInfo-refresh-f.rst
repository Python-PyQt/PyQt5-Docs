.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: cfc527d1efd4570fe049e80795224525

Resets :sip:ref:`~PyQt5.QtCore.QStorageInfo`'s internal cache.

:sip:ref:`~PyQt5.QtCore.QStorageInfo` caches information about storage to speed up performance. :sip:ref:`~PyQt5.QtCore.QStorageInfo` retrieves information during object construction and/or when calling the setPath() method. You have to manually reset the cache by calling this function to update storage information.
