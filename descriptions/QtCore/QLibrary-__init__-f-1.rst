.. sip:method-description::
    :status: todo
    :pysig: d5bbb8e095a63981f86b3ce5298e6ca3
    :realsig: (const QString&,QObject*)
    :digest: 610ba9f3a95eaba89493fc3d91803bb0

Constructs a library object with the given *parent* that will load the library specified by *fileName*.

We recommend omitting the file's suffix in *fileName*, since :sip:ref:`~PyQt5.QtCore.QLibrary` will automatically look for the file with the appropriate suffix in accordance with the platform, e.g. ".so" on Unix, ".dylib" on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS, and ".dll" on Windows. (See :sip:ref:`~PyQt5.QtCore.QLibrary.fileName`.)
