.. sip:method-description::
    :status: todo
    :pysig: e5ddef5a540d03b40da26a1b30c1c8d7
    :realsig: (QWidget*,const QGLWidget*,Qt::WindowFlags)
    :digest: 53a248cdec151860d79437820dc0d162

Constructs an OpenGL widget with a *parent* widget.

The :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultFormat` is used. The widget will be :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isValid` if the system has no :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.hasOpenGL`.

The *parent* and widget flag, *f*, arguments are passed to the :sip:ref:`~PyQt5.QtWidgets.QWidget` constructor.

If *shareWidget* is a valid :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`, this widget will share OpenGL display lists and texture objects with *shareWidget*. But if *shareWidget* and this widget have different :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.format`, sharing might not be possible. You can check whether sharing is in effect by calling :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isSharing`.

The initialization of OpenGL rendering state, etc. should be done by overriding the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` function, rather than in the constructor of your :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` subclass.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultFormat`, `Textures Example <https://doc.qt.io/qt-5/qtopengl-textures-example.html>`_.
