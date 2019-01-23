.. sip:method-description::
    :status: todo
    :pysig: 60725cce91dc24aea72c05bb61f4dfe9
    :realsig: (const QGLFormat&)
    :digest: 69221d3b104ed713b3d06e714eee57f3

Sets a *format* for this context. The context is :sip:ref:`~PyQt5.QtOpenGL.QGLContext.reset`.

Call :sip:ref:`~PyQt5.QtOpenGL.QGLContext.create` to create a new GL context that tries to match the new format.

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 128-136

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.reset`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.create`.
