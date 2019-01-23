.. sip:enum-member-description::
    :status: todo
    :value: 0x0000000a | Window
    :digest: dd98f3307b60adb048bde51057f87d26

Indicates that the widget is a tool window. A tool window is often a small window with a smaller than usual title bar and decoration, typically used for collections of tool buttons. If there is a parent, the tool window will always be kept on top of it. If there isn't a parent, you may consider using  as well. If the window system supports it, a tool window can be decorated with a somewhat lighter frame. It can also be combined with . On `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, tool windows correspond to the NSPanel class of windows. This means that the window lives on a level above normal windows making it impossible to put a normal window on top of it. By default, tool windows will disappear when the application is inactive. This can be controlled by the :sip:ref:`~PyQt5.QtCore.Qt.WidgetAttribute.WA_MacAlwaysShowToolWindow` attribute.
