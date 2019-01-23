.. sip:enum-description::
    :status: todo
    :digest: 8a1b238849c91b12359c00f74d8ef96a

This enum type is used to specify various window-system properties for the widget. They are fairly unusual but necessary in a few cases. Some of these flags depend on whether the underlying window manager supports them.

The main types are

There are also a number of flags which you can use to customize the appearance of top-level windows. These have no effect on other windows:

The ``CustomizeWindowHint`` flag is used to enable customization of the window controls. This flag must be set to allow the ``WindowTitleHint``, ``WindowSystemMenuHint``, ``WindowMinimizeButtonHint``, ``WindowMaximizeButtonHint`` and ``WindowCloseButtonHint`` flags to be changed.

**Note:** On X11, this hint will work only in window managers that support _NET_WM_STATE_BELOW atom. If a window always on the bottom has a parent, the parent will also be left on the bottom. This window hint is currently not implemented for `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_.

**Note:** On Windows, this will work only for frameless or full-screen windows.

.. seealso:: :sip:ref:`~PyQt5.QtWidgets.QWidget.windowFlags`, `Window Flags Example <https://doc.qt.io/qt-5/qtwidgets-widgets-windowflags-example.html>`_.
