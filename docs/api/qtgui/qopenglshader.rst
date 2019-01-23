:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLShader
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QOpenGLShader-c.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLShader.ShaderTypeBit
        :description: QtGui/QOpenGLShader-ShaderTypeBit-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLShader.ShaderTypeBit.Compute
            :description: QtGui/QOpenGLShader-ShaderTypeBit-Compute-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLShader.ShaderTypeBit.Fragment
            :description: QtGui/QOpenGLShader-ShaderTypeBit-Fragment-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLShader.ShaderTypeBit.Geometry
            :description: QtGui/QOpenGLShader-ShaderTypeBit-Geometry-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLShader.ShaderTypeBit.TessellationControl
            :description: QtGui/QOpenGLShader-ShaderTypeBit-TessellationControl-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLShader.ShaderTypeBit.TessellationEvaluation
            :description: QtGui/QOpenGLShader-ShaderTypeBit-TessellationEvaluation-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLShader.ShaderTypeBit.Vertex
            :description: QtGui/QOpenGLShader-ShaderTypeBit-Vertex-v.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QOpenGLShader-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.compileSourceCode
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            bool
        :description: QtGui/QOpenGLShader-compileSourceCode-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.compileSourceCode
        :args:
            str
        :returns:
            bool
        :description: QtGui/QOpenGLShader-compileSourceCode-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.compileSourceFile
        :args:
            str
        :returns:
            bool
        :description: QtGui/QOpenGLShader-compileSourceFile-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.hasOpenGLShaders
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            context: :sip:ref:`~PyQt5.QtGui.QOpenGLContext` = None
        :returns:
            bool
        :static:
        :description: QtGui/QOpenGLShader-hasOpenGLShaders-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.isCompiled
        :returns:
            bool
        :description: QtGui/QOpenGLShader-isCompiled-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.log
        :returns:
            str
        :description: QtGui/QOpenGLShader-log-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.shaderId
        :returns:
            int
        :description: QtGui/QOpenGLShader-shaderId-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.shaderType
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`
        :description: QtGui/QOpenGLShader-shaderType-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShader.sourceCode
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtGui/QOpenGLShader-sourceCode-f.rst
