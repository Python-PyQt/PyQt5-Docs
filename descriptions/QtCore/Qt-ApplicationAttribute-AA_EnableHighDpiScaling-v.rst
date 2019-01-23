.. sip:enum-member-description::
    :status: todo
    :value: TODO
    :digest: 42d2a1fa790aeeeafee3da64c834c45a

Enables high-DPI scaling in Qt on supported platforms (see also High DPI Displays). Supported platforms are X11, Windows and Android. Enabling makes Qt scale the main (device independent) coordinate system according to display scale factors provided by the operating system. This corresponds to setting the QT_AUTO_SCREEN​_SCALE_FACTOR environment variable to 1. This attribute must be set before :sip:ref:`~PyQt5.QtGui.QGuiApplication` is constructed. This value was added in Qt 5.6.
