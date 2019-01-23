.. sip:method-description::
    :status: todo
    :pysig: 29d4f5c84f5879ed952c735bcb5e0153
    :realsig: ()
    :digest: 0d218a7f74500a85643d743c74bd5bdd

Returns the application-wide shared OpenGL context, if present. Otherwise, returns a null pointer.

This is useful if you need to upload OpenGL objects (buffers, textures, etc.) before creating or showing a QOpenGLWidget or QQuickWidget.

**Note:** You must set the Qt::AA_ShareOpenGLContexts flag on :sip:ref:`~PyQt5.QtGui.QGuiApplication` before creating the :sip:ref:`~PyQt5.QtGui.QGuiApplication` object, otherwise Qt may not create a global shared context.

**Warning:** Do not attempt to make the context returned by this function current on any surface. Instead, you can create a new context which shares with the global one, and then make the new context current.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLContext.setShareContext`, :sip:ref:`~PyQt5.QtGui.QOpenGLContext.makeCurrent`, Qt::AA_ShareOpenGLContexts.
