.. sip:method-description::
    :status: todo
    :pysig: 5998d438b579c18b701076e06b760c58
    :realsig: (QOpenGLShader*)
    :digest: 22b4da44522613879366a1c04954840c

Adds a compiled *shader* to this shader program. Returns ``true`` if the shader could be added, or false otherwise.

Ownership of the *shader* object remains with the caller. It will not be deleted when this :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram` instance is deleted. This allows the caller to add the same shader to multiple shader programs.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceFile`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.removeShader`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.link`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.removeAllShaders`.
