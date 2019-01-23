.. sip:method-description::
    :status: todo
    :pysig: 60725cce91dc24aea72c05bb61f4dfe9
    :realsig: (const QGLFormat&)
    :digest: fa1fecf3b259c232f90180f8dbbf3e11

Constructs an OpenGL context with the given *format* which specifies several display options for the context.

If the underlying OpenGL/Window system cannot satisfy all the features requested in *format*, the nearest subset of features will be used. After creation, the :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format` method will return the actual format obtained.

Note that after a :sip:ref:`~PyQt5.QtOpenGL.QGLContext` object has been constructed, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.create` must be called explicitly to create the actual OpenGL context. The context will be :sip:ref:`~PyQt5.QtOpenGL.QGLContext.isValid` if it was not possible to obtain a GL context at all.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.isValid`.
