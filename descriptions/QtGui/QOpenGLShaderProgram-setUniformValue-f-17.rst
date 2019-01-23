.. sip:method-description::
    :status: todo
    :pysig: 74f2ab2e0e39e8be90b7370a553e10da
    :realsig: (int,const QMatrix4x3&)
    :digest: 380dc62504ce4ce9d2ebd31fc519432d

Sets the uniform variable at *location* in the current context to a 4x3 matrix *value*.

**Note:** This function is not aware of non square matrix support, that is, GLSL types like mat4x3, that is present in modern OpenGL versions. Instead, it treats the uniform as an array of vec3.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue`.
