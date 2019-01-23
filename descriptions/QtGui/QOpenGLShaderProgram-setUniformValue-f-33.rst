.. sip:method-description::
    :status: todo
    :pysig: baf5780fb6fc4d4f29ae08b10cd3c26f
    :realsig: (const char*,const QMatrix3x2&)
    :digest: 7daa27923387fbe57da8e988fd1e9cd3

This is an overloaded function.

Sets the uniform variable called *name* in the current context to a 3x2 matrix *value*.

**Note:** This function is not aware of non square matrix support, that is, GLSL types like mat3x2, that is present in modern OpenGL versions. Instead, it treats the uniform as an array of vec2.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue`.
