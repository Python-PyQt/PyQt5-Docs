.. sip:method-description::
    :status: todo
    :pysig: 0155a5a66917c743fc062e69c4cbd87f
    :realsig: (QGL::FormatOptions,int)
    :digest: 70a3ba77f16661a2b5ba3dcc412547b9

Creates a :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` object that is a copy of the current :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultFormat`.

If *options* is not 0, the default format is modified by the specified format options. The *options* parameter should be :sip:ref:`~PyQt5.QtOpenGL.QGL.FormatOption` values OR'ed together.

This constructor makes it easy to specify a certain desired format in classes derived from :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`, for example:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 84-94

Note that there are :sip:ref:`~PyQt5.QtOpenGL.QGL.FormatOption` values to turn format settings both on and off, e.g. :sip:ref:`~PyQt5.QtOpenGL.QGL.FormatOption.DepthBuffer` and :sip:ref:`~PyQt5.QtOpenGL.QGL.FormatOption.NoDepthBuffer`, :sip:ref:`~PyQt5.QtOpenGL.QGL.FormatOption.DirectRendering` and :sip:ref:`~PyQt5.QtOpenGL.QGL.FormatOption.IndirectRendering`, etc.

The *plane* parameter defaults to 0 and is the plane which this format should be associated with. Not all OpenGL implementations supports overlay/underlay rendering planes.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.defaultFormat`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setOption`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setPlane`.
