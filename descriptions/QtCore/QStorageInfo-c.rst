.. sip:class-description::
    :status: todo
    :brief: Provides information about currently mounted storage and drives
    :digest: 72eb7ae832efb7bb35a2ebda2de67aa7

Provides information about currently mounted storage and drives.

Allows retrieving information about the volume's space, its mount point, label, and filesystem name.

You can create an instance of :sip:ref:`~PyQt5.QtCore.QStorageInfo` by passing the path to the volume's mount point as a constructor parameter, or you can set it using the setPath() method. The static :sip:ref:`~PyQt5.QtCore.QStorageInfo.mountedVolumes` method can be used to get the list of all mounted filesystems.

:sip:ref:`~PyQt5.QtCore.QStorageInfo` always caches the retrieved information, but you can call :sip:ref:`~PyQt5.QtCore.QStorageInfo.refresh` to invalidate the cache.

The following example retrieves the most common information about the root volume of the system, and prints information about it.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qstorageinfo.py
    :lines: 60-69
