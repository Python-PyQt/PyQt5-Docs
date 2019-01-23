.. sip:method-description::
    :status: todo
    :pysig: 17465268f977311a157ca3716c7f2c68
    :realsig: (QGLContext*,QWidget*,const QGLWidget*,Qt::WindowFlags)
    :digest: d87a09b4ef627e6ce7010e9b52536996

Constructs an OpenGL widget with parent *parent*.

The *context* argument is a pointer to the :sip:ref:`~PyQt5.QtOpenGL.QGLContext` that you wish to be bound to this widget. This allows you to pass in your own :sip:ref:`~PyQt5.QtOpenGL.QGLContext` sub-classes.

The widget will be :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isValid` if the system has no :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.hasOpenGL`.

The *parent* and widget flag, *f*, arguments are passed to the :sip:ref:`~PyQt5.QtWidgets.QWidget` constructor.

If *shareWidget* is a valid :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`, this widget will share OpenGL display lists and texture objects with *shareWidget*. But if *shareWidget* and this widget have different :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.format`, sharing might not be possible. You can check whether sharing is in effect by calling :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isSharing`.

The initialization of OpenGL rendering state, etc. should be done by overriding the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` function, rather than in the constructor of your :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` subclass.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultFormat`, :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isValid`.
