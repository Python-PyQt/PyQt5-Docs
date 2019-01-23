.. sip:class-description::
    :status: todo
    :brief: Information about the system
    :digest: ec923e3f4568a67108ad35784462bef6

The :sip:ref:`~PyQt5.QtCore.QSysInfo` class provides information about the system.

* :sip:ref:`~PyQt5.QtCore.QSysInfo.Sizes.WordSize` specifies the size of a pointer for the platform on which the application is compiled.

* :sip:ref:`~PyQt5.QtCore.QSysInfo.Endian.ByteOrder` specifies whether the platform is big-endian or little-endian.

Some constants are defined only on certain platforms. You can use the preprocessor symbols Q_OS_WIN and Q_OS_MACOS to test that the application is compiled under Windows or `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QLibraryInfo`.
