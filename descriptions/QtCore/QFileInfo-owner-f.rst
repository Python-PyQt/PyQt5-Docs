.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: 7cad566accd852d4a755d5918a9677f0

Returns the owner of the file. On systems where files do not have owners, or if an error occurs, an empty string is returned.

This function can be time consuming under Unix (in the order of milliseconds). On Windows, it will return an empty string unless the :ref:`NTFS permissions<qfileinfo-ntfs-permissions>` check has been enabled.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.ownerId`, :sip:ref:`~PyQt5.QtCore.QFileInfo.group`, :sip:ref:`~PyQt5.QtCore.QFileInfo.groupId`.
