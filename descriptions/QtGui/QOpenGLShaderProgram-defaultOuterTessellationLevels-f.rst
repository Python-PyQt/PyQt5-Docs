.. sip:method-description::
    :status: todo
    :pysig: 021dbd5510a963cb43170a72ca7d4949
    :realsig: () const
    :digest: 50a649c612a787dec3e9f2e7123b5cf4

Returns the default outer tessellation levels to be used by the tessellation primitive generator in the event that the tessellation control shader does not output them. For more details on OpenGL and Tessellation shaders see `OpenGL Tessellation Shaders <https://doc.qt.io/qt-5/http://www.opengl.org/wiki/Tessellation_Shader>`_.

Returns a QVector of floats describing the outer tessellation levels. The vector will always have four elements but not all of them make sense for every mode of tessellation.

**Note:** This returns the global OpenGL state value. It is not specific to this :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram` instance.

**Note:** This function is only supported with OpenGL >= 4.0 and will not return valid results with OpenGL ES 3.2.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.setDefaultOuterTessellationLevels`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.defaultInnerTessellationLevels`.
