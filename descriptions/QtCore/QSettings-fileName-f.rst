.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: 1c1dc7b893252c2e70e003dabb72cffa

Returns the path where settings written using this :sip:ref:`~PyQt5.QtCore.QSettings` object are stored.

On Windows, if the format is QSettings::NativeFormat, the return value is a system registry path, not a file path.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSettings.isWritable`, :sip:ref:`~PyQt5.QtCore.QSettings.format`.
