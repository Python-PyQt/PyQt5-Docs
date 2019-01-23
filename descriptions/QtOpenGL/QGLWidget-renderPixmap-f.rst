.. sip:method-description::
    :status: todo
    :pysig: 00a7bec1fe63bd0319b14fd24fe55996
    :realsig: (int,int,bool)
    :digest: e5e62664ed0582e7ecacf9a63b796e32

Renders the current scene on a pixmap and returns the pixmap.

You can use this method on both visible and invisible :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` objects.

Internally the function renders into a framebuffer object and performs pixel readback. This has a performance penalty, meaning that this function is not suitable to be called at a high frequency.

After creating and binding the framebuffer object, the function will call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL`, :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeGL`, and :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL`. On the next normal update :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` and :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeGL` will be triggered again since the size of the destination pixmap and the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`'s size may differ.

The size of the pixmap will be *w* pixels wide and *h* pixels high unless one of these parameters is 0 (the default), in which case the pixmap will have the same size as the widget.

Care must be taken when using framebuffer objects in :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` in combination with this function. To switch back to the default framebuffer, use QGLFramebufferObject::bindDefault(). Binding FBO 0 is wrong since  uses a custom framebuffer instead of the one provided by the windowing system.

*useContext* is ignored. Historically this parameter enabled the usage of the existing GL context. This is not supported anymore since additional contexts are never created.

Overlays are not rendered onto the pixmap.

If the GL rendering context and the desktop have different bit depths, the result will most likely look surprising.

Note that the creation of display lists, modifications of the view frustum etc. should be done from within :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL`. If this is not done, the temporary :sip:ref:`~PyQt5.QtOpenGL.QGLContext` will not be initialized properly, and the rendered pixmap may be incomplete/corrupted.
