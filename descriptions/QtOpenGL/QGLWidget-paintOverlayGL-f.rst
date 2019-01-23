.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 5dec590fd85de9a6f19440be9a285d4e

This virtual function is used in the same manner as :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` except that it operates on the widget's overlay context instead of the widget's main context. This means that  is called whenever the widget's overlay needs to be painted. Reimplement it in a subclass.

There is no need to call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.makeOverlayCurrent` because this has already been done when this function is called.
