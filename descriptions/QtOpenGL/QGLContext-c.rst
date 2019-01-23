.. sip:class-description::
    :status: todo
    :brief: Encapsulates an OpenGL rendering context
    :digest: 9fddc2854a298432609b381e5088d777

The :sip:ref:`~PyQt5.QtOpenGL.QGLContext` class encapsulates an OpenGL rendering context.

An OpenGL rendering context is a complete set of OpenGL state variables. The rendering context's :sip:ref:`~PyQt5.QtOpenGL.QGL.FormatOption` is set in the constructor, but it can also be set later with :sip:ref:`~PyQt5.QtOpenGL.QGLContext.setFormat`. The format options that are actually set are returned by :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format`; the options you asked for are returned by :sip:ref:`~PyQt5.QtOpenGL.QGLContext.requestedFormat`. Note that after a :sip:ref:`~PyQt5.QtOpenGL.QGLContext` object has been constructed, the actual OpenGL context must be created by explicitly calling the :sip:ref:`~PyQt5.QtOpenGL.QGLContext.create` function. The :sip:ref:`~PyQt5.QtOpenGL.QGLContext.makeCurrent` function makes this context the current rendering context. You can make *no* context current using :sip:ref:`~PyQt5.QtOpenGL.QGLContext.doneCurrent`. The :sip:ref:`~PyQt5.QtOpenGL.QGLContext.reset` function will reset the context and make it invalid.

You can examine properties of the context with, e.g. :sip:ref:`~PyQt5.QtOpenGL.QGLContext.isValid`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.isSharing`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.initialized`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.windowCreated` and :sip:ref:`~PyQt5.QtOpenGL.QGLContext.overlayTransparentColor`.

If you're using double buffering you can swap the screen contents with the off-screen buffer using :sip:ref:`~PyQt5.QtOpenGL.QGLContext.swapBuffers`.

Please note that :sip:ref:`~PyQt5.QtOpenGL.QGLContext` is not thread safe.
