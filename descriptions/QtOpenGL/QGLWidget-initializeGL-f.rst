.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: a2eb09442f363c82612ba75bae170e0e

This virtual function is called once before the first call to :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` or :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeGL`, and then once whenever the widget has been assigned a new :sip:ref:`~PyQt5.QtOpenGL.QGLContext`. Reimplement it in a subclass.

This function should set up any required OpenGL context rendering flags, defining display lists, etc.

There is no need to call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.makeCurrent` because this has already been done when this function is called.
