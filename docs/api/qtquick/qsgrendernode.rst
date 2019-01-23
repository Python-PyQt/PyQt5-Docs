:orphan:

.. sip:class:: PyQt5.QtQuick.QSGRenderNode
    :inherits: :sip:ref:`~PyQt5.QtQuick.QSGNode`
    :description: QtQuick/QSGRenderNode-c.rst

    .. sip:enum:: PyQt5.QtQuick.QSGRenderNode.RenderingFlag
        :description: QtQuick/QSGRenderNode-RenderingFlag-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.RenderingFlag.BoundedRectRendering
            :description: QtQuick/QSGRenderNode-RenderingFlag-BoundedRectRendering-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.RenderingFlag.DepthAwareRendering
            :description: QtQuick/QSGRenderNode-RenderingFlag-DepthAwareRendering-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.RenderingFlag.OpaqueRendering
            :description: QtQuick/QSGRenderNode-RenderingFlag-OpaqueRendering-v.rst

    .. sip:enum:: PyQt5.QtQuick.QSGRenderNode.StateFlag
        :description: QtQuick/QSGRenderNode-StateFlag-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.BlendState
            :description: QtQuick/QSGRenderNode-StateFlag-BlendState-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.ColorState
            :description: QtQuick/QSGRenderNode-StateFlag-ColorState-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.CullState
            :description: QtQuick/QSGRenderNode-StateFlag-CullState-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.DepthState
            :description: QtQuick/QSGRenderNode-StateFlag-DepthState-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.RenderTargetState
            :description: QtQuick/QSGRenderNode-StateFlag-RenderTargetState-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.ScissorState
            :description: QtQuick/QSGRenderNode-StateFlag-ScissorState-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.StencilState
            :description: QtQuick/QSGRenderNode-StateFlag-StencilState-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGRenderNode.StateFlag.ViewportState
            :description: QtQuick/QSGRenderNode-StateFlag-ViewportState-v.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.changedStates
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGRenderNode.StateFlags`
        :description: QtQuick/QSGRenderNode-changedStates-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.clipList
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGClipNode`
        :description: QtQuick/QSGRenderNode-clipList-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.flags
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGRenderNode.RenderingFlags`
        :description: QtQuick/QSGRenderNode-flags-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.inheritedOpacity
        :returns:
            float
        :description: QtQuick/QSGRenderNode-inheritedOpacity-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.matrix
        :returns:
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
        :description: QtQuick/QSGRenderNode-matrix-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.rect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtQuick/QSGRenderNode-rect-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.releaseResources
        :description: QtQuick/QSGRenderNode-releaseResources-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGRenderNode.render
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGRenderNode.RenderState`
        :description: QtQuick/QSGRenderNode-render-f.rst
