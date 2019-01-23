.. sip:method-description::
    :status: todo
    :pysig: 6359afdf86b9ec14316ea3f79e266b65
    :realsig: () const
    :digest: e1149bb317296ba2961b954f79f4294a

Returns the device for this volume.

For example, on Unix filesystems (including `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_), this returns the devpath like ``/dev/sda0`` for local storages. On Windows, it returns the UNC path starting with ``\\\\?\\`` for local storages (in other words, the volume GUID).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStorageInfo.rootPath`, :sip:ref:`~PyQt5.QtCore.QStorageInfo.subvolume`.
