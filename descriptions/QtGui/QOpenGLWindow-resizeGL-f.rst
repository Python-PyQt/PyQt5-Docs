.. sip:method-description::
    :status: todo
    :pysig: 61569f2965b7a369eb10b6d75d410d11
    :realsig: (int,int)
    :digest: dd4c343b353c507f9ac80be1f6f80a89

This virtual function is called whenever the widget has been resized. Reimplement it in a subclass. The new size is passed in *w* and *h*.

**Note:** This is merely a convenience function in order to provide an API that is compatible with QOpenGLWidget. Unlike with QOpenGLWidget, derived classes are free to choose to override :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.resizeEvent` instead of this function.

**Note:** Avoid issuing OpenGL commands from this function as there may not be a context current when it is invoked. If it cannot be avoided, call :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.makeCurrent`.

**Note:** Scheduling updates from here is not necessary. The windowing systems will send expose events that trigger an update automatically.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.initializeGL`, :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintGL`.
