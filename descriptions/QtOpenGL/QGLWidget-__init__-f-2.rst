.. sip:method-description::
    :status: todo
    :pysig: d6c7a0b57a430ed1ebe51be2ee39064b
    :realsig: (const QGLFormat&,QWidget*,const QGLWidget*,Qt::WindowFlags)
    :digest: 153a43f322d1bcf9ca1fea29c62e5242

Constructs an OpenGL widget with parent *parent*.

The *format* argument specifies the desired :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`. If the underlying OpenGL/Window system cannot satisfy all the features requested in *format*, the nearest subset of features will be used. After creation, the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.format` method will return the actual format obtained.

The widget will be :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isValid` if the system has no :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.hasOpenGL`.

The *parent* and widget flag, *f*, arguments are passed to the :sip:ref:`~PyQt5.QtWidgets.QWidget` constructor.

If *shareWidget* is a valid :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`, this widget will share OpenGL display lists and texture objects with *shareWidget*. But if *shareWidget* and this widget have different :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.format`, sharing might not be possible. You can check whether sharing is in effect by calling :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isSharing`.

The initialization of OpenGL rendering state, etc. should be done by overriding the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` function, rather than in the constructor of your :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` subclass.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultFormat`, :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isValid`.
