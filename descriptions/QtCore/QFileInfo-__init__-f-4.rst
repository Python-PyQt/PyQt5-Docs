.. sip:method-description::
    :status: todo
    :pysig: 0fe572559f10136b32fc2bcabd810f2e
    :realsig: (const QDir&,const QString&)
    :digest: 6fa6457a4402a1596b4e3b1b635b26e8

Constructs a new :sip:ref:`~PyQt5.QtCore.QFileInfo` that gives information about the given *file* in the directory *dir*.

If *dir* has a relative path, the :sip:ref:`~PyQt5.QtCore.QFileInfo` will also have a relative path.

If *file* is an absolute path, then the directory specified by *dir* will be disregarded.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.isRelative`.
