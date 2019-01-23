.. sip:method-description::
    :status: todo
    :pysig: b073eba90d83e4b7c501a1c0830e149b
    :realsig: (const char*,const QMatrix4x3&)
    :digest: 7daa27923387fbe57da8e988fd1e9cd3

This is an overloaded function.

Sets the uniform variable called *name* in the current context to a 4x3 matrix *value*.

**Note:** This function is not aware of non square matrix support, that is, GLSL types like mat4x3, that is present in modern OpenGL versions. Instead, it treats the uniform as an array of vec3.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue`.
