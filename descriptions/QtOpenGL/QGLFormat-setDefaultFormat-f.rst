.. sip:method-description::
    :status: todo
    :pysig: df1cdba42ded00101db045e2b92d4144
    :realsig: (const QGLFormat&)
    :digest: ac1b167f57bb3b5d2c4f27b0b56db293

Sets a new default :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` for the application to *f*. For example, to set single buffering as the default instead of double buffering, your main() might contain code like this:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 99-102

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultFormat`.
