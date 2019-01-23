.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 3a34b44bb2f046224902ef208b9e41e3

Returns ``true`` if the user can read the file; otherwise returns ``false``.

**Note:** If the :ref:`NTFS permissions<qfileinfo-ntfs-permissions>` check has not been enabled, the result on Windows will merely reflect whether the file exists.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.isWritable`, :sip:ref:`~PyQt5.QtCore.QFileInfo.isExecutable`, :sip:ref:`~PyQt5.QtCore.QFileInfo.permission`.
