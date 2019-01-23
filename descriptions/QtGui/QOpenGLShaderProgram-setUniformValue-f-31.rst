.. sip:method-description::
    :status: todo
    :pysig: 05fc7ac44786fd2434590a1e6e9011ad
    :realsig: (const char*,const QMatrix2x3&)
    :digest: 7daa27923387fbe57da8e988fd1e9cd3

This is an overloaded function.

Sets the uniform variable called *name* in the current context to a 2x3 matrix *value*.

**Note:** This function is not aware of non square matrix support, that is, GLSL types like mat2x3, that is present in modern OpenGL versions. Instead, it treats the uniform as an array of vec3.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue`.
