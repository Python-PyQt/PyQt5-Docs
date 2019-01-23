.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 4c067217c7abe3c009a6520b4d284d2f

This virtual function is called whenever the widget needs to be painted. Reimplement it in a subclass.

There is no need to call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.makeCurrent` because this has already been done when this function is called.
