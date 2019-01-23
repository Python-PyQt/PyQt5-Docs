.. sip:method-description::
    :status: todo
    :pysig: 6359afdf86b9ec14316ea3f79e266b65
    :realsig: () const
    :digest: b9fee33e380e32ccb6a6796c23b3c981

Returns the type name of the filesystem.

This is a platform-dependent function, and filesystem names can vary between different operating systems. For example, on Windows filesystems they can be named ``NTFS``, and on Linux they can be named ``ntfs-3g`` or ``fuseblk``.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStorageInfo.name`.
