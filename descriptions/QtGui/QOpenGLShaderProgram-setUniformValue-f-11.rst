.. sip:method-description::
    :status: todo
    :pysig: bc3d4fd8f18bd2a3f3db35bf152843cc
    :realsig: (int,const QMatrix2x3&)
    :digest: 380dc62504ce4ce9d2ebd31fc519432d

Sets the uniform variable at *location* in the current context to a 2x3 matrix *value*.

**Note:** This function is not aware of non square matrix support, that is, GLSL types like mat2x3, that is present in modern OpenGL versions. Instead, it treats the uniform as an array of vec3.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue`.
