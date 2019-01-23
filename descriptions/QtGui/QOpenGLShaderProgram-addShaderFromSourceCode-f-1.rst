.. sip:method-description::
    :status: todo
    :pysig: 0c9fe45bb71607fc2000450125a44efb
    :realsig: (QOpenGLShader::ShaderType,const QString&)
    :digest: 7b4c0fef8ab57d43fb6ba5e061a48c17

This is an overloaded function.

Compiles *source* as a shader of the specified *type* and adds it to this shader program. Returns ``true`` if compilation was successful, false otherwise. The compilation errors and warnings will be made available via :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.log`.

This function is intended to be a short-cut for quickly adding vertex and fragment shaders to a shader program without creating an instance of :sip:ref:`~PyQt5.QtGui.QOpenGLShader` first.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShader`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceFile`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.removeShader`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.log`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.removeAllShaders`.
