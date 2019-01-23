.. sip:method-description::
    :status: todo
    :pysig: e39a72093dade11c0c475606858f1693
    :realsig: ()
    :digest: ab31fad58692c83a4f4cce4102b7f92a

Identifies, at runtime, which OpenGL versions that are supported by the current platform.

Note that if OpenGL version 1.5 is supported, its predecessors (i.e., version 1.4 and lower) are also supported. To identify the support of a particular feature, like multi texturing, test for the version in which the feature was first introduced (i.e., version 1.3 in the case of multi texturing) to adapt to the largest possible group of runtime platforms.

This function needs a valid current OpenGL context to work; otherwise it will return :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.OpenGLVersionFlag.OpenGL_Version_None`.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.hasOpenGL`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.hasOpenGLOverlays`.
