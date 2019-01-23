.. sip:method-description::
    :status: todo
    :pysig: 0c9fe45bb71607fc2000450125a44efb
    :realsig: (QOpenGLShader::ShaderType,const QString&)
    :digest: c85af1a234f8234724f3ea20400b67b8

Registers the shader of the specified *type* and *fileName* to this program. Unlike :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceFile`, this function does not perform compilation. Compilation is deferred to :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link`, and may not happen at all, because :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link` may potentially use a program binary from Qt's shader disk cache. This will typically lead to a significant increase in performance.

Returns true if the file has been read successfully, false if the file could not be opened or the normal, non-cached compilation of the shader has failed. The compilation error messages can be retrieved via :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.log`.

When the disk cache is disabled, via Qt::AA_DisableShaderDiskCache for example, or the OpenGL context has no support for context binaries, calling this function is equivalent to :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceFile`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceFile`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addCacheableShaderFromSourceCode`.
