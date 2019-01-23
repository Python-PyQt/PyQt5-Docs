:orphan:

.. sip:class:: PyQt5.Qt3DRender.QBuffer
    :inherits: :sip:ref:`~PyQt5.Qt3DCore.QNode`
    :description: Qt3DRender/QBuffer-c.rst

    .. sip:enum:: PyQt5.Qt3DRender.QBuffer.AccessType
        :description: Qt3DRender/QBuffer-AccessType-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.AccessType.Read
            :description: Qt3DRender/QBuffer-AccessType-Read-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.AccessType.ReadWrite
            :description: Qt3DRender/QBuffer-AccessType-ReadWrite-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.AccessType.Write
            :description: Qt3DRender/QBuffer-AccessType-Write-v.rst

    .. sip:enum:: PyQt5.Qt3DRender.QBuffer.BufferType
        :description: Qt3DRender/QBuffer-BufferType-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.BufferType.DrawIndirectBuffer
            :description: Qt3DRender/QBuffer-BufferType-DrawIndirectBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.BufferType.IndexBuffer
            :description: Qt3DRender/QBuffer-BufferType-IndexBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.BufferType.PixelPackBuffer
            :description: Qt3DRender/QBuffer-BufferType-PixelPackBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.BufferType.PixelUnpackBuffer
            :description: Qt3DRender/QBuffer-BufferType-PixelUnpackBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.BufferType.ShaderStorageBuffer
            :description: Qt3DRender/QBuffer-BufferType-ShaderStorageBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.BufferType.UniformBuffer
            :description: Qt3DRender/QBuffer-BufferType-UniformBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.BufferType.VertexBuffer
            :description: Qt3DRender/QBuffer-BufferType-VertexBuffer-v.rst

    .. sip:enum:: PyQt5.Qt3DRender.QBuffer.UsageType
        :description: Qt3DRender/QBuffer-UsageType-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.DynamicCopy
            :description: Qt3DRender/QBuffer-UsageType-DynamicCopy-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.DynamicDraw
            :description: Qt3DRender/QBuffer-UsageType-DynamicDraw-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.DynamicRead
            :description: Qt3DRender/QBuffer-UsageType-DynamicRead-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.StaticCopy
            :description: Qt3DRender/QBuffer-UsageType-StaticCopy-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.StaticDraw
            :description: Qt3DRender/QBuffer-UsageType-StaticDraw-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.StaticRead
            :description: Qt3DRender/QBuffer-UsageType-StaticRead-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.StreamCopy
            :description: Qt3DRender/QBuffer-UsageType-StreamCopy-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.StreamDraw
            :description: Qt3DRender/QBuffer-UsageType-StreamDraw-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QBuffer.UsageType.StreamRead
            :description: Qt3DRender/QBuffer-UsageType-StreamRead-v.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.__init__
        :args:
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DRender/QBuffer-__init__-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.__init__
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.BufferType`
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DRender/QBuffer-__init__-f-1.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.accessType
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.AccessType`
        :description: Qt3DRender/QBuffer-accessType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.data
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: Qt3DRender/QBuffer-data-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.dataGenerator
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QBufferDataGenerator`
        :description: Qt3DRender/QBuffer-dataGenerator-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.isSyncData
        :returns:
            bool
        :description: Qt3DRender/QBuffer-isSyncData-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.sceneChangeEvent
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QSceneChange`
        :description: Qt3DRender/QBuffer-sceneChangeEvent-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.setAccessType
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.AccessType`
        :description: Qt3DRender/QBuffer-setAccessType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.setData
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: Qt3DRender/QBuffer-setData-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.setDataGenerator
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBufferDataGenerator`
        :description: Qt3DRender/QBuffer-setDataGenerator-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.setSyncData
        :args:
            bool
        :description: Qt3DRender/QBuffer-setSyncData-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.setType
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.BufferType`
        :description: Qt3DRender/QBuffer-setType-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.setUsage
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.UsageType`
        :description: Qt3DRender/QBuffer-setUsage-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.type
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.BufferType`
        :description: Qt3DRender/QBuffer-type-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.updateData
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: Qt3DRender/QBuffer-updateData-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QBuffer.usage
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.UsageType`
        :description: Qt3DRender/QBuffer-usage-f.rst

    .. sip:signal:: PyQt5.Qt3DRender.QBuffer.accessTypeChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.AccessType`
        :description: Qt3DRender/QBuffer-accessTypeChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QBuffer.dataAvailable
        :description: Qt3DRender/QBuffer-dataAvailable-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QBuffer.dataChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: Qt3DRender/QBuffer-dataChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QBuffer.syncDataChanged
        :args:
            bool
        :description: Qt3DRender/QBuffer-syncDataChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QBuffer.typeChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.BufferType`
        :description: Qt3DRender/QBuffer-typeChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QBuffer.usageChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QBuffer.UsageType`
        :description: Qt3DRender/QBuffer-usageChanged-s.rst
