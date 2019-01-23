.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 6c8a8235a4b83c80749e6f25cc5dcf43

This virtual function is used in the same manner as :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` except that it operates on the widget's overlay context instead of the widget's main context. This means that  is called once before the first call to :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintOverlayGL` or :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeOverlayGL`. Reimplement it in a subclass.

This function should set up any required OpenGL context rendering flags, defining display lists, etc. for the overlay context.

There is no need to call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.makeOverlayCurrent` because this has already been done when this function is called.
