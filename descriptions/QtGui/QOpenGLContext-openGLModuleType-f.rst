.. sip:method-description::
    :status: todo
    :pysig: 3d1fa9412044e92afbcf7e51779f989b
    :realsig: ()
    :digest: b3f1e5a4ae60860bce045b55833f95ee

Returns the underlying OpenGL implementation type.

On platforms where the OpenGL implementation is not dynamically loaded, the return value is determined during compile time and never changes.

**Note:** A desktop OpenGL implementation may be capable of creating ES-compatible contexts too. Therefore in most cases it is more appropriate to check :sip:ref:`~PyQt5.QtGui.QSurfaceFormat.renderableType` or use the convenience function :sip:ref:`~PyQt5.QtGui.QOpenGLContext.isOpenGLES`.

**Note:** This function requires that the :sip:ref:`~PyQt5.QtGui.QGuiApplication` instance is already created.
