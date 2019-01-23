.. sip:method-description::
    :status: todo
    :pysig: 1bf2bbb7a4c3d8aca6fda0e345d560a6
    :realsig: (const char*,const QMatrix4x2&)
    :digest: 7daa27923387fbe57da8e988fd1e9cd3

This is an overloaded function.

Sets the uniform variable called *name* in the current context to a 4x2 matrix *value*.

**Note:** This function is not aware of non square matrix support, that is, GLSL types like mat4x2, that is present in modern OpenGL versions. Instead, it treats the uniform as an array of vec2.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue`.
