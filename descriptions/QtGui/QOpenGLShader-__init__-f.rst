.. sip:method-description::
    :status: todo
    :pysig: 836e9597bc6950623aac255ad3668634
    :realsig: (QOpenGLShader::ShaderType,QObject*)
    :digest: a1966a5d084833342293c2dd8b310834

Constructs a new :sip:ref:`~PyQt5.QtGui.QOpenGLShader` object of the specified *type* and attaches it to *parent*. If shader programs are not supported, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.hasOpenGLShaderPrograms` will return false.

This constructor is normally followed by a call to :sip:ref:`~PyQt5.QtGui.QOpenGLShader.compileSourceCode` or :sip:ref:`~PyQt5.QtGui.QOpenGLShader.compileSourceFile`.

The shader will be associated with the current :sip:ref:`~PyQt5.QtGui.QOpenGLContext`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShader.compileSourceCode`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.compileSourceFile`.
