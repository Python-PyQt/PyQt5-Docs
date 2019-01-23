.. sip:method-description::
    :status: todo
    :pysig: 241570b1770b58701e098a8a190c0b61
    :realsig: (const QString&,const QString&,QObject*)
    :digest: d5ea1c93841e05b80f550c02c3c2900c

Constructs a library object with the given *parent* that will load the library specified by *fileName* and full version number *version*. Currently, the version number is ignored on Windows.

We recommend omitting the file's suffix in *fileName*, since :sip:ref:`~PyQt5.QtCore.QLibrary` will automatically look for the file with the appropriate suffix in accordance with the platform, e.g. ".so" on Unix, ".dylib" on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS, and ".dll" on Windows. (See :sip:ref:`~PyQt5.QtCore.QLibrary.fileName`.)
