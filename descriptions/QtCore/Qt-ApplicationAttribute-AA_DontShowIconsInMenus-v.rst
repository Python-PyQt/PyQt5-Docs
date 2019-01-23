.. sip:enum-member-description::
    :status: todo
    :value: 2
    :digest: dd637c4ea3cf5ca0c8738b6325a1450a

Actions with the Icon property won't be shown in any menus unless specifically set by the QAction::iconVisibleInMenu property. Menus that are currently open or menus already created in the native `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ menubar *may not* pick up a change in this attribute. Changes in the QAction::iconVisibleInMenu property will always be picked up.
