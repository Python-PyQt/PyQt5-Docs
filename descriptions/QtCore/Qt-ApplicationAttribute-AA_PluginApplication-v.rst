.. sip:enum-member-description::
    :status: todo
    :value: TODO
    :digest: 380fda19d7e1d9977dceecb019734605

Indicates that Qt is used to author a plugin. Depending on the operating system, it suppresses specific initializations that do not necessarily make sense in the plugin case. For example on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, this includes avoiding loading our nib for the main menu and not taking possession of the native menu bar. Setting this attribute to true will also set the  attribute to true. It also disables native event filters. This attribute must be set before :sip:ref:`~PyQt5.QtGui.QGuiApplication` constructed. This value was added in Qt 5.7.
