.. sip:method-description::
    :status: todo
    :pysig: f619129584fe7150dc9ac770389b5b52
    :realsig: (const QPixmap&,Qt::DropAction)
    :digest: 9ad0ccf527b550037360e2908db16fbd

Sets the drag *cursor* for the *action*. This allows you to override the default native cursors. To revert to using the native cursor for *action* pass in a null :sip:ref:`~PyQt5.QtGui.QPixmap` as *cursor*.

Note: setting the drag cursor for IgnoreAction may not work on all platforms. X11 and `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ has been tested to work. Windows does not support it.
