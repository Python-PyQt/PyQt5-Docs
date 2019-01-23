.. sip:method-description::
    :status: todo
    :pysig: 0c9fe45bb71607fc2000450125a44efb
    :realsig: (QOpenGLShader::ShaderType,const QString&)
    :digest: aa299ec49c85b4ab473f0bfeebc6a2e6

Compiles the contents of *fileName* as a shader of the specified *type* and adds it to this shader program. Returns ``true`` if compilation was successful, false otherwise. The compilation errors and warnings will be made available via :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.log`.

This function is intended to be a short-cut for quickly adding vertex and fragment shaders to a shader program without creating an instance of :sip:ref:`~PyQt5.QtGui.QOpenGLShader` first.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShader`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`.
