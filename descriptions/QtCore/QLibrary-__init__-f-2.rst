.. sip:method-description::
    :status: todo
    :pysig: cc08544b0a4eafecf7c050a7f53fae0a
    :realsig: (const QString&,int,QObject*)
    :digest: e5177adf0c065c3805bdf69a3d6e5c6b

Constructs a library object with the given *parent* that will load the library specified by *fileName* and major version number *verNum*. Currently, the version number is ignored on Windows.

We recommend omitting the file's suffix in *fileName*, since :sip:ref:`~PyQt5.QtCore.QLibrary` will automatically look for the file with the appropriate suffix in accordance with the platform, e.g. ".so" on Unix, ".dylib" on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS, and ".dll" on Windows. (See :sip:ref:`~PyQt5.QtCore.QLibrary.fileName`.)
