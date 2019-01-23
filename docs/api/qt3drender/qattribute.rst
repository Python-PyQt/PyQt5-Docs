:orphan:

.. sip:class:: PyQt5.Qt3DRender.QAttribute
    :inherits: :sip:ref:`~PyQt5.Qt3DCore.QNode`
    :description: Qt3DRender/QAttribute-c.rst

    .. sip:enum:: PyQt5.Qt3DRender.QAttribute.AttributeType
        :description: Qt3DRender/QAttribute-AttributeType-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.AttributeType.DrawIndirectAttribute
            :description: Qt3DRender/QAttribute-AttributeType-DrawIndirectAttribute-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.AttributeType.IndexAttribute
            :description: Qt3DRender/QAttribute-AttributeType-IndexAttribute-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.AttributeType.VertexAttribute
            :description: Qt3DRender/QAttribute-AttributeType-VertexAttribute-v.rst

    .. sip:enum:: PyQt5.Qt3DRender.QAttribute.VertexBaseType
        :description: Qt3DRender/QAttribute-VertexBaseType-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.Byte
            :description: Qt3DRender/QAttribute-VertexBaseType-Byte-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.Double
            :description: Qt3DRender/QAttribute-VertexBaseType-Double-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.Float
            :description: Qt3DRender/QAttribute-VertexBaseType-Float-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.HalfFloat
            :description: Qt3DRender/QAttribute-VertexBaseType-HalfFloat-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.Int
            :description: Qt3DRender/QAttribute-VertexBaseType-Int-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.Short
            :description: Qt3DRender/QAttribute-VertexBaseType-Short-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.UnsignedByte
            :description: Qt3DRender/QAttribute-VertexBaseType-UnsignedByte-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.UnsignedInt
            :description: Qt3DRender/QAttribute-VertexBaseType-UnsignedInt-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAttribute.VertexBaseType.UnsignedShort
            :description: Qt3DRender/QAttribute-VertexBaseType-UnsignedShort-v.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.__init__
        :args:
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DRender/QAttribute-__init__-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.__init__
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer`
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.VertexBaseType`
            int
            int
            offset: int = 0
            stride: int = 0
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DRender/QAttribute-__init__-f-1.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.__init__
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer`
            str
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.VertexBaseType`
            int
            int
            offset: int = 0
            stride: int = 0
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DRender/QAttribute-__init__-f-2.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.attributeType
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.AttributeType`
        :description: Qt3DRender/QAttribute-attributeType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.buffer
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer`
        :description: Qt3DRender/QAttribute-buffer-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.byteOffset
        :returns:
            int
        :description: Qt3DRender/QAttribute-byteOffset-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.byteStride
        :returns:
            int
        :description: Qt3DRender/QAttribute-byteStride-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.count
        :returns:
            int
        :description: Qt3DRender/QAttribute-count-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultColorAttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultColorAttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultJointIndicesAttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultJointIndicesAttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultJointWeightsAttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultJointWeightsAttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultNormalAttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultNormalAttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultPositionAttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultPositionAttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultTangentAttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultTangentAttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultTextureCoordinate1AttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultTextureCoordinate1AttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultTextureCoordinate2AttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultTextureCoordinate2AttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.defaultTextureCoordinateAttributeName
        :returns:
            str
        :static:
        :description: Qt3DRender/QAttribute-defaultTextureCoordinateAttributeName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.divisor
        :returns:
            int
        :description: Qt3DRender/QAttribute-divisor-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.name
        :returns:
            str
        :description: Qt3DRender/QAttribute-name-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setAttributeType
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.AttributeType`
        :description: Qt3DRender/QAttribute-setAttributeType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setBuffer
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer`
        :description: Qt3DRender/QAttribute-setBuffer-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setByteOffset
        :args:
            int
        :description: Qt3DRender/QAttribute-setByteOffset-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setByteStride
        :args:
            int
        :description: Qt3DRender/QAttribute-setByteStride-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setCount
        :args:
            int
        :description: Qt3DRender/QAttribute-setCount-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setDataSize
        :args:
            int
        :description: Qt3DRender/QAttribute-setDataSize-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setDataType
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.VertexBaseType`
        :description: Qt3DRender/QAttribute-setDataType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setDivisor
        :args:
            int
        :description: Qt3DRender/QAttribute-setDivisor-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setName
        :args:
            str
        :description: Qt3DRender/QAttribute-setName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setVertexBaseType
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.VertexBaseType`
        :description: Qt3DRender/QAttribute-setVertexBaseType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.setVertexSize
        :args:
            int
        :description: Qt3DRender/QAttribute-setVertexSize-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.vertexBaseType
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.VertexBaseType`
        :description: Qt3DRender/QAttribute-vertexBaseType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAttribute.vertexSize
        :returns:
            int
        :description: Qt3DRender/QAttribute-vertexSize-f.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.attributeTypeChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.AttributeType`
        :description: Qt3DRender/QAttribute-attributeTypeChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.bufferChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer`
        :description: Qt3DRender/QAttribute-bufferChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.byteOffsetChanged
        :args:
            int
        :description: Qt3DRender/QAttribute-byteOffsetChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.byteStrideChanged
        :args:
            int
        :description: Qt3DRender/QAttribute-byteStrideChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.countChanged
        :args:
            int
        :description: Qt3DRender/QAttribute-countChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.dataSizeChanged
        :args:
            int
        :description: Qt3DRender/QAttribute-dataSizeChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.dataTypeChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.VertexBaseType`
        :description: Qt3DRender/QAttribute-dataTypeChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.divisorChanged
        :args:
            int
        :description: Qt3DRender/QAttribute-divisorChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.nameChanged
        :args:
            str
        :description: Qt3DRender/QAttribute-nameChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.vertexBaseTypeChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QAttribute.VertexBaseType`
        :description: Qt3DRender/QAttribute-vertexBaseTypeChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAttribute.vertexSizeChanged
        :args:
            int
        :description: Qt3DRender/QAttribute-vertexSizeChanged-s.rst
