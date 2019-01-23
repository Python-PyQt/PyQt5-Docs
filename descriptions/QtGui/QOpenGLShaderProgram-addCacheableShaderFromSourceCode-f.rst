.. sip:method-description::
    :status: todo
    :pysig: b37b2838ee95b424bdbbbd650d86d704
    :realsig: (QOpenGLShader::ShaderType,const QByteArray&)
    :digest: 0a1de45edb13ba933a6dac0d1edee277

This is an overloaded function.

Registers the shader of the specified *type* and *source* to this program. Unlike :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`, this function does not perform compilation. Compilation is deferred to :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link`, and may not happen at all, because :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link` may potentially use a program binary from Qt's shader disk cache. This will typically lead to a significant increase in performance.

Returns true if the shader has been registered or, in the non-cached case, compiled successfully; false if there was an error. The compilation error messages can be retrieved via :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.log`.

When the disk cache is disabled, via Qt::AA_DisableShaderDiskCache for example, or the OpenGL context has no support for context binaries, calling this function is equivalent to :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addCacheableShaderFromSourceFile`.
