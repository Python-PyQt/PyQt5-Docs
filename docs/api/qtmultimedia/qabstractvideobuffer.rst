:orphan:

.. sip:class:: PyQt5.QtMultimedia.QAbstractVideoBuffer
    :description: QtMultimedia/QAbstractVideoBuffer-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType
        :description: QtMultimedia/QAbstractVideoBuffer-HandleType-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.CoreImageHandle
            :description: QtMultimedia/QAbstractVideoBuffer-HandleType-CoreImageHandle-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.EGLImageHandle
            :description: QtMultimedia/QAbstractVideoBuffer-HandleType-EGLImageHandle-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.GLTextureHandle
            :description: QtMultimedia/QAbstractVideoBuffer-HandleType-GLTextureHandle-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.NoHandle
            :description: QtMultimedia/QAbstractVideoBuffer-HandleType-NoHandle-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.QPixmapHandle
            :description: QtMultimedia/QAbstractVideoBuffer-HandleType-QPixmapHandle-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.UserHandle
            :description: QtMultimedia/QAbstractVideoBuffer-HandleType-UserHandle-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.XvShmImageHandle
            :description: QtMultimedia/QAbstractVideoBuffer-HandleType-XvShmImageHandle-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode
        :description: QtMultimedia/QAbstractVideoBuffer-MapMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode.NotMapped
            :description: QtMultimedia/QAbstractVideoBuffer-MapMode-NotMapped-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode.ReadOnly
            :description: QtMultimedia/QAbstractVideoBuffer-MapMode-ReadOnly-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode.ReadWrite
            :description: QtMultimedia/QAbstractVideoBuffer-MapMode-ReadWrite-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode.WriteOnly
            :description: QtMultimedia/QAbstractVideoBuffer-MapMode-WriteOnly-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoBuffer.__init__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType`
        :description: QtMultimedia/QAbstractVideoBuffer-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoBuffer.handle
        :returns:
            Any
        :description: QtMultimedia/QAbstractVideoBuffer-handle-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoBuffer.handleType
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType`
        :description: QtMultimedia/QAbstractVideoBuffer-handleType-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoBuffer.map
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode`
        :returns:
            PyQt5.sip.voidptr
            int
            int
        :description: QtMultimedia/QAbstractVideoBuffer-map-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoBuffer.mapMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode`
        :description: QtMultimedia/QAbstractVideoBuffer-mapMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoBuffer.release
        :description: QtMultimedia/QAbstractVideoBuffer-release-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoBuffer.unmap
        :description: QtMultimedia/QAbstractVideoBuffer-unmap-f.rst
