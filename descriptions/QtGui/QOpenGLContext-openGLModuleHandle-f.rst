.. sip:method-description::
    :status: todo
    :pysig: d9a675468278ba0b4a48902f19589aa5
    :realsig: ()
    :digest: 894d2e847a90c599a345cb7c697e8ae7

Returns the platform-specific handle for the OpenGL implementation that is currently in use. (for example, a HMODULE on Windows)

On platforms that do not use dynamic GL switch the return value is null.

The library might be GL-only, meaning that windowing system interface functions (for example EGL) may live in another, separate library.

**Note:** This function requires that the :sip:ref:`~PyQt5.QtGui.QGuiApplication` instance is already created.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLContext.openGLModuleType`.
