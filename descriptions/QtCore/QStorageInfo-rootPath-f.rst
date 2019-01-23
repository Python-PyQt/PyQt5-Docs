.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: 791e713b21e27166cda6d5fa55f290a3

Returns the mount point of the filesystem this :sip:ref:`~PyQt5.QtCore.QStorageInfo` object represents.

On Windows, it returns the volume letter in case the volume is not mounted to a directory.

Note that the value returned by  is the real mount point of a volume, and may not be equal to the value passed to the constructor or setPath() method. For example, if you have only the root volume in the system, and pass '/directory' to setPath(), then this method will return '/'.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStorageInfo.device`, :sip:ref:`~PyQt5.QtCore.QStorageInfo.setPath`.
