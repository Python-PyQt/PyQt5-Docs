:orphan:

.. sip:class:: PyQt5.Qt3DRender.QMemoryBarrier
    :inherits: :sip:ref:`~PyQt5.Qt3DRender.QFrameGraphNode`
    :description: Qt3DRender/QMemoryBarrier-c.rst

    .. sip:enum:: PyQt5.Qt3DRender.QMemoryBarrier.Operation
        :description: Qt3DRender/QMemoryBarrier-Operation-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.All
            :description: Qt3DRender/QMemoryBarrier-Operation-All-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.AtomicCounter
            :description: Qt3DRender/QMemoryBarrier-Operation-AtomicCounter-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.BufferUpdate
            :description: Qt3DRender/QMemoryBarrier-Operation-BufferUpdate-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.Command
            :description: Qt3DRender/QMemoryBarrier-Operation-Command-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.ElementArray
            :description: Qt3DRender/QMemoryBarrier-Operation-ElementArray-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.FrameBuffer
            :description: Qt3DRender/QMemoryBarrier-Operation-FrameBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.None_
            :description: Qt3DRender/QMemoryBarrier-Operation-None_-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.PixelBuffer
            :description: Qt3DRender/QMemoryBarrier-Operation-PixelBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.QueryBuffer
            :description: Qt3DRender/QMemoryBarrier-Operation-QueryBuffer-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.ShaderImageAccess
            :description: Qt3DRender/QMemoryBarrier-Operation-ShaderImageAccess-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.ShaderStorage
            :description: Qt3DRender/QMemoryBarrier-Operation-ShaderStorage-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.TextureFetch
            :description: Qt3DRender/QMemoryBarrier-Operation-TextureFetch-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.TextureUpdate
            :description: Qt3DRender/QMemoryBarrier-Operation-TextureUpdate-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.TransformFeedback
            :description: Qt3DRender/QMemoryBarrier-Operation-TransformFeedback-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.Uniform
            :description: Qt3DRender/QMemoryBarrier-Operation-Uniform-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMemoryBarrier.Operation.VertexAttributeArray
            :description: Qt3DRender/QMemoryBarrier-Operation-VertexAttributeArray-v.rst

    .. sip:method:: PyQt5.Qt3DRender.QMemoryBarrier.__init__
        :args:
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DRender/QMemoryBarrier-__init__-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMemoryBarrier.setWaitOperations
        :args:
            Union[:sip:ref:`~PyQt5.Qt3DRender.QMemoryBarrier.Operations`, :sip:ref:`~PyQt5.Qt3DRender.QMemoryBarrier.Operation`]
        :description: Qt3DRender/QMemoryBarrier-setWaitOperations-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMemoryBarrier.waitOperations
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QMemoryBarrier.Operations`
        :description: Qt3DRender/QMemoryBarrier-waitOperations-f.rst

    .. sip:signal:: PyQt5.Qt3DRender.QMemoryBarrier.waitOperationsChanged
        :args:
            Union[:sip:ref:`~PyQt5.Qt3DRender.QMemoryBarrier.Operations`, :sip:ref:`~PyQt5.Qt3DRender.QMemoryBarrier.Operation`]
        :description: Qt3DRender/QMemoryBarrier-waitOperationsChanged-s.rst
