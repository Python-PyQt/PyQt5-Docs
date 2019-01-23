.. sip:method-description::
    :status: todo
    :pysig: df1cdba42ded00101db045e2b92d4144
    :realsig: (const QGLFormat&)
    :digest: e64819690ea5190fc64be5112aa11482

Sets a new default :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` for overlay contexts to *f*. This format is used whenever a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` is created with a format that :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.hasOverlay` enabled.

For example, to get a double buffered overlay context (if available), use code like this:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 107-109

As usual, you can find out after widget creation whether the underlying OpenGL system was able to provide the requested specification:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 114-123

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultOverlayFormat`.
