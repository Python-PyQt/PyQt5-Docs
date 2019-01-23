.. sip:method-description::
    :status: todo
    :pysig: 52b09f81a3c6b5744ef09e679710d485
    :realsig: (const QIcon&)
    :digest: e35fba9f538fba097a11c3ba20c8e1af

Sets the window's *icon* in the windowing system

The window icon might be used by the windowing system for example to decorate the window, and/or in the task switcher.

**Note:** On `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, the window title bar icon is meant for windows representing documents, and will only show up if a file path is also set.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.icon`, :sip:ref:`~PyQt5.QtGui.QWindow.setFilePath`.
