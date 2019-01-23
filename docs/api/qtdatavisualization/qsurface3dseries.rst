:orphan:

.. sip:class:: PyQt5.QtDataVisualization.QSurface3DSeries
    :inherits: :sip:ref:`~PyQt5.QtDataVisualization.QAbstract3DSeries`
    :description: QtDataVisualization/QSurface3DSeries-c.rst

    .. sip:enum:: PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlag
        :description: QtDataVisualization/QSurface3DSeries-DrawFlag-e.rst

        .. sip:enum-member:: PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlag.DrawSurface
            :description: QtDataVisualization/QSurface3DSeries-DrawFlag-DrawSurface-v.rst

        .. sip:enum-member:: PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlag.DrawSurfaceAndWireframe
            :description: QtDataVisualization/QSurface3DSeries-DrawFlag-DrawSurfaceAndWireframe-v.rst

        .. sip:enum-member:: PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlag.DrawWireframe
            :description: QtDataVisualization/QSurface3DSeries-DrawFlag-DrawWireframe-v.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtDataVisualization/QSurface3DSeries-__init__-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.__init__
        :args:
            :sip:ref:`~PyQt5.QtDataVisualization.QSurfaceDataProxy`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtDataVisualization/QSurface3DSeries-__init__-f-1.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.dataProxy
        :returns:
            :sip:ref:`~PyQt5.QtDataVisualization.QSurfaceDataProxy`
        :description: QtDataVisualization/QSurface3DSeries-dataProxy-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.drawMode
        :returns:
            :sip:ref:`~PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlags`
        :description: QtDataVisualization/QSurface3DSeries-drawMode-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.invalidSelectionPosition
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :static:
        :description: QtDataVisualization/QSurface3DSeries-invalidSelectionPosition-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.isFlatShadingEnabled
        :returns:
            bool
        :description: QtDataVisualization/QSurface3DSeries-isFlatShadingEnabled-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.isFlatShadingSupported
        :returns:
            bool
        :description: QtDataVisualization/QSurface3DSeries-isFlatShadingSupported-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.selectedPoint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtDataVisualization/QSurface3DSeries-selectedPoint-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.setDataProxy
        :args:
            :sip:ref:`~PyQt5.QtDataVisualization.QSurfaceDataProxy`
        :description: QtDataVisualization/QSurface3DSeries-setDataProxy-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.setDrawMode
        :args:
            Union[:sip:ref:`~PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlags`, :sip:ref:`~PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlag`]
        :description: QtDataVisualization/QSurface3DSeries-setDrawMode-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.setFlatShadingEnabled
        :args:
            bool
        :description: QtDataVisualization/QSurface3DSeries-setFlatShadingEnabled-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.setSelectedPoint
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtDataVisualization/QSurface3DSeries-setSelectedPoint-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.setTexture
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtDataVisualization/QSurface3DSeries-setTexture-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.setTextureFile
        :args:
            str
        :description: QtDataVisualization/QSurface3DSeries-setTextureFile-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.texture
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtDataVisualization/QSurface3DSeries-texture-f.rst

    .. sip:method:: PyQt5.QtDataVisualization.QSurface3DSeries.textureFile
        :returns:
            str
        :description: QtDataVisualization/QSurface3DSeries-textureFile-f.rst

    .. sip:signal:: PyQt5.QtDataVisualization.QSurface3DSeries.dataProxyChanged
        :args:
            :sip:ref:`~PyQt5.QtDataVisualization.QSurfaceDataProxy`
        :description: QtDataVisualization/QSurface3DSeries-dataProxyChanged-s.rst

    .. sip:signal:: PyQt5.QtDataVisualization.QSurface3DSeries.drawModeChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlags`, :sip:ref:`~PyQt5.QtDataVisualization.QSurface3DSeries.DrawFlag`]
        :description: QtDataVisualization/QSurface3DSeries-drawModeChanged-s.rst

    .. sip:signal:: PyQt5.QtDataVisualization.QSurface3DSeries.flatShadingEnabledChanged
        :args:
            bool
        :description: QtDataVisualization/QSurface3DSeries-flatShadingEnabledChanged-s.rst

    .. sip:signal:: PyQt5.QtDataVisualization.QSurface3DSeries.flatShadingSupportedChanged
        :args:
            bool
        :description: QtDataVisualization/QSurface3DSeries-flatShadingSupportedChanged-s.rst

    .. sip:signal:: PyQt5.QtDataVisualization.QSurface3DSeries.selectedPointChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtDataVisualization/QSurface3DSeries-selectedPointChanged-s.rst

    .. sip:signal:: PyQt5.QtDataVisualization.QSurface3DSeries.textureChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtDataVisualization/QSurface3DSeries-textureChanged-s.rst

    .. sip:signal:: PyQt5.QtDataVisualization.QSurface3DSeries.textureFileChanged
        :args:
            str
        :description: QtDataVisualization/QSurface3DSeries-textureFileChanged-s.rst
