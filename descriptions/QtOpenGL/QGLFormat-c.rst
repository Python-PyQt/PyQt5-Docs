.. sip:class-description::
    :status: todo
    :brief: Specifies the display format of an OpenGL rendering context
    :digest: be79f6dc0abf2b6ab60b79aa3ac2fe3b

The :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` class specifies the display format of an OpenGL rendering context.

A display format has several characteristics:

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDoubleBuffer`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDepth`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setRgba`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setAlpha`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setAccum`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setStencil`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setStereo`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDirectRendering`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setOverlay`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setPlane`

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setSampleBuffers`

You can also specify preferred bit depths for the color buffer, depth buffer, alpha buffer, accumulation buffer and the stencil buffer with the functions: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setRedBufferSize`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setGreenBufferSize`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setBlueBufferSize`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDepthBufferSize`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setAlphaBufferSize`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setAccumBufferSize` and :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setStencilBufferSize`.

Note that even if you specify that you prefer a 32 bit depth buffer (e.g. with :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDepthBufferSize`\ (32)), the format that is chosen may not have a 32 bit depth buffer, even if there is a format available with a 32 bit depth buffer. The main reason for this is how the system dependant picking algorithms work on the different platforms, and some format options may have higher precedence than others.

You create and tell a :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` object what rendering options you want from an OpenGL rendering context.

OpenGL drivers or accelerated hardware may or may not support advanced features such as alpha channel or stereographic viewing. If you request some features that the driver/hardware does not provide when you create a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`, you will get a rendering context with the nearest subset of features.

There are different ways to define the display characteristics of a rendering context. One is to create a :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` and make it the default for the entire application:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 54-57

Or you can specify the desired format when creating an object of your :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` subclass:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 62-65

After the widget has been created, you can find out which of the requested features the system was able to provide:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 70-79

.. container:: legalese

    OpenGL is a trademark of Silicon Graphics, Inc. in the United States and other countries.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLContext`, :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`.
