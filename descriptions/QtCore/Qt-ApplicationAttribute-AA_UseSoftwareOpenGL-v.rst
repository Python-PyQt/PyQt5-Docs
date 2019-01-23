.. sip:enum-member-description::
    :status: todo
    :value: TODO
    :digest: 6550a03c23c228151b7c83cf3b698cb0

Forces the usage of a software based OpenGL implementation on platforms that use dynamic loading of the OpenGL implementation. This will typically be a patched build of Mesa llvmpipe, providing OpenGL 2.1. The value may have no effect if no such OpenGL implementation is available. The default name of this library is ``opengl32sw.dll`` and can be overridden by setting the environment variable *QT_OPENGL_DLL*. See the platform-specific pages, for instance Qt for Windows, for more information. This attribute must be set before :sip:ref:`~PyQt5.QtGui.QGuiApplication` is constructed. This value was added in Qt 5.4.
