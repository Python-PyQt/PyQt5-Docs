.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: 0d77d3f37656c4b3f29173f02621ef21

Sets the requested plane to *plane*. 0 is the normal plane, 1 is the first overlay plane, 2 is the second overlay plane, etc.; -1, -2, etc. are underlay planes.

Note that in contrast to other format specifications, the plane specifications will be matched exactly. This means that if you specify a plane that the underlying OpenGL system cannot provide, an :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.isValid` :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` will be created.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.plane`.
