.. sip:method-description::
    :status: todo
    :pysig: 0c9fe45bb71607fc2000450125a44efb
    :realsig: (QOpenGLShader::ShaderType,const QString&)
    :digest: 6a62d8ea86216657aa6d8e98d1b0e473

This is an overloaded function.

Registers the shader of the specified *type* and *source* to this program. Unlike :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`, this function does not perform compilation. Compilation is deferred to :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link`, and may not happen at all, because :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link` may potentially use a program binary from Qt's shader disk cache. This will typically lead to a significant increase in performance.

When the disk cache is disabled, via Qt::AA_DisableShaderDiskCache for example, or the OpenGL context has no support for context binaries, calling this function is equivalent to :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addCacheableShaderFromSourceFile`.
