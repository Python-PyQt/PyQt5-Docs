:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLShaderProgram
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QOpenGLShaderProgram-c.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QOpenGLShaderProgram-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.addCacheableShaderFromSourceCode
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-addCacheableShaderFromSourceCode-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.addCacheableShaderFromSourceCode
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            str
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-addCacheableShaderFromSourceCode-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.addCacheableShaderFromSourceFile
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            str
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-addCacheableShaderFromSourceFile-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.addShader
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLShader`
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-addShader-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-addShaderFromSourceCode-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceCode
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            str
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-addShaderFromSourceCode-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.addShaderFromSourceFile
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderType`, :sip:ref:`~PyQt5.QtGui.QOpenGLShader.ShaderTypeBit`]
            str
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-addShaderFromSourceFile-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.attributeLocation
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            int
        :description: QtGui/QOpenGLShaderProgram-attributeLocation-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.attributeLocation
        :args:
            str
        :returns:
            int
        :description: QtGui/QOpenGLShaderProgram-attributeLocation-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.bind
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-bind-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.bindAttributeLocation
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            int
        :description: QtGui/QOpenGLShaderProgram-bindAttributeLocation-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.bindAttributeLocation
        :args:
            str
            int
        :description: QtGui/QOpenGLShaderProgram-bindAttributeLocation-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.create
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-create-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.defaultInnerTessellationLevels
        :returns:
            List[float]
        :description: QtGui/QOpenGLShaderProgram-defaultInnerTessellationLevels-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.defaultOuterTessellationLevels
        :returns:
            List[float]
        :description: QtGui/QOpenGLShaderProgram-defaultOuterTessellationLevels-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.disableAttributeArray
        :args:
            int
        :description: QtGui/QOpenGLShaderProgram-disableAttributeArray-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.disableAttributeArray
        :args:
            str
        :description: QtGui/QOpenGLShaderProgram-disableAttributeArray-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.enableAttributeArray
        :args:
            int
        :description: QtGui/QOpenGLShaderProgram-enableAttributeArray-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.enableAttributeArray
        :args:
            str
        :description: QtGui/QOpenGLShaderProgram-enableAttributeArray-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.hasOpenGLShaderPrograms
        :args:
            context: :sip:ref:`~PyQt5.QtGui.QOpenGLContext` = None
        :returns:
            bool
        :static:
        :description: QtGui/QOpenGLShaderProgram-hasOpenGLShaderPrograms-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.isLinked
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-isLinked-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.link
        :returns:
            bool
        :description: QtGui/QOpenGLShaderProgram-link-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.log
        :returns:
            str
        :description: QtGui/QOpenGLShaderProgram-log-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.maxGeometryOutputVertices
        :returns:
            int
        :description: QtGui/QOpenGLShaderProgram-maxGeometryOutputVertices-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.patchVertexCount
        :returns:
            int
        :description: QtGui/QOpenGLShaderProgram-patchVertexCount-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.programId
        :returns:
            int
        :description: QtGui/QOpenGLShaderProgram-programId-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.release
        :description: QtGui/QOpenGLShaderProgram-release-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.removeAllShaders
        :description: QtGui/QOpenGLShaderProgram-removeAllShaders-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.removeShader
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLShader`
        :description: QtGui/QOpenGLShaderProgram-removeShader-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeArray
        :args:
            int
            PYQT_SHADER_ATTRIBUTE_ARRAY
        :description: QtGui/QOpenGLShaderProgram-setAttributeArray-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeArray
        :args:
            str
            PYQT_SHADER_ATTRIBUTE_ARRAY
        :description: QtGui/QOpenGLShaderProgram-setAttributeArray-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeBuffer
        :args:
            int
            int
            int
            int
            stride: int = 0
        :description: QtGui/QOpenGLShaderProgram-setAttributeBuffer-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeBuffer
        :args:
            str
            int
            int
            int
            stride: int = 0
        :description: QtGui/QOpenGLShaderProgram-setAttributeBuffer-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QVector2D`
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QVector3D`
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-2.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QVector4D`
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-3.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-4.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-5.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QVector2D`
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-6.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QVector3D`
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-7.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QVector4D`
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-8.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-9.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-10.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-11.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-12.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-13.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            int
            float
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-14.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setAttributeValue
        :args:
            str
            float
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setAttributeValue-f-15.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setDefaultInnerTessellationLevels
        :args:
            Iterable[float]
        :description: QtGui/QOpenGLShaderProgram-setDefaultInnerTessellationLevels-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setDefaultOuterTessellationLevels
        :args:
            Iterable[float]
        :description: QtGui/QOpenGLShaderProgram-setDefaultOuterTessellationLevels-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setPatchVertexCount
        :args:
            int
        :description: QtGui/QOpenGLShaderProgram-setPatchVertexCount-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            int
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QVector2D`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-2.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QVector3D`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-3.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QVector4D`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-4.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-5.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-6.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-7.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-8.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QSizeF`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-9.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix2x2`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-10.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix2x3`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-11.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix2x4`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-12.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix3x2`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-13.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix3x3`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-14.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix3x4`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-15.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix4x2`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-16.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix4x3`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-17.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-18.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-19.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            int
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-20.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-21.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QVector2D`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-22.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QVector3D`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-23.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QVector4D`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-24.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-25.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-26.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-27.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-28.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QSizeF`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-29.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix2x2`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-30.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix2x3`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-31.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix2x4`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-32.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix3x2`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-33.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix3x3`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-34.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix3x4`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-35.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix4x2`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-36.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix4x3`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-37.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-38.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-39.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-40.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-41.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-42.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-43.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            int
            float
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-44.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValue
        :args:
            str
            float
            float
            float
            float
        :description: QtGui/QOpenGLShaderProgram-setUniformValue-f-45.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValueArray
        :args:
            int
            PYQT_SHADER_UNIFORM_VALUE_ARRAY
        :description: QtGui/QOpenGLShaderProgram-setUniformValueArray-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.setUniformValueArray
        :args:
            str
            PYQT_SHADER_UNIFORM_VALUE_ARRAY
        :description: QtGui/QOpenGLShaderProgram-setUniformValueArray-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.shaders
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QOpenGLShader`]
        :description: QtGui/QOpenGLShaderProgram-shaders-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.uniformLocation
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            int
        :description: QtGui/QOpenGLShaderProgram-uniformLocation-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLShaderProgram.uniformLocation
        :args:
            str
        :returns:
            int
        :description: QtGui/QOpenGLShaderProgram-uniformLocation-f-1.rst
