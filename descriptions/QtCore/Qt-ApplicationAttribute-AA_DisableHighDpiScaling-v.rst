.. sip:enum-member-description::
    :status: todo
    :value: TODO
    :digest: 62fd074285542ff548b8e22617b3b126

Disables high-DPI scaling in Qt, exposing window system coordinates. Note that the window system may do its own scaling, so this does not guarantee that QPaintDevice::devicePixelRatio() will be equal to 1. In addition, scale factors set by QT_SCALE_FACTOR will not be affected. This corresponds to setting the QT_AUTO_SCREEN​_SCALE_FACTOR environment variable to 0. This attribute must be set before :sip:ref:`~PyQt5.QtGui.QGuiApplication` is constructed. This value was added in Qt 5.6.
