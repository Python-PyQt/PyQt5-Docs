.. sip:method-description::
    :status: todo
    :pysig: a2c9c20642aa78a0611ed11a12391483
    :realsig: (QOpenGLContext*)
    :digest: 84ee619ab2ca0a83810a54e2ffcb32be

Returns ``true`` if shader programs written in the OpenGL Shading Language (GLSL) are supported on this system; false otherwise.

The *context* is used to resolve the GLSL extensions. If *context* is null, then :sip:ref:`~PyQt5.QtGui.QOpenGLContext.currentContext` is used.
