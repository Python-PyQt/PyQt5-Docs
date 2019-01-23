.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 4a884f91917daf88b456d1dd608c0132

Returns ``true`` if the user can write to the file; otherwise returns ``false``.

**Note:** If the :ref:`NTFS permissions<qfileinfo-ntfs-permissions>` check has not been enabled, the result on Windows will merely reflect whether the file is marked as Read Only.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.isReadable`, :sip:ref:`~PyQt5.QtCore.QFileInfo.isExecutable`, :sip:ref:`~PyQt5.QtCore.QFileInfo.permission`.
