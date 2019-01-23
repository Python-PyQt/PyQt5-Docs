.. sip:method-description::
    :status: todo
    :pysig: 9e9d5625f3f82c3a91054bf4740d2529
    :realsig: (int,const QMatrix3x2&)
    :digest: 380dc62504ce4ce9d2ebd31fc519432d

Sets the uniform variable at *location* in the current context to a 3x2 matrix *value*.

**Note:** This function is not aware of non square matrix support, that is, GLSL types like mat3x2, that is present in modern OpenGL versions. Instead, it treats the uniform as an array of vec2.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue`.
