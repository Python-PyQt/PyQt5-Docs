.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: de87d3e78b97b51e96e62fb0fbe6e8d3

Returns the file's path. This doesn't include the file name.

Note that, if this :sip:ref:`~PyQt5.QtCore.QFileInfo` object is given a path ending in a slash, the name of the file is considered empty and this function will return the entire path.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.filePath`, :sip:ref:`~PyQt5.QtCore.QFileInfo.absolutePath`, :sip:ref:`~PyQt5.QtCore.QFileInfo.canonicalPath`, :sip:ref:`~PyQt5.QtCore.QFileInfo.dir`, :sip:ref:`~PyQt5.QtCore.QFileInfo.fileName`, :sip:ref:`~PyQt5.QtCore.QFileInfo.isRelative`.
