:orphan:

.. sip:class:: PyQt5.QtMultimedia.QVideoSurfaceFormat
    :description: QtMultimedia/QVideoSurfaceFormat-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QVideoSurfaceFormat.Direction
        :description: QtMultimedia/QVideoSurfaceFormat-Direction-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.Direction.BottomToTop
            :description: QtMultimedia/QVideoSurfaceFormat-Direction-BottomToTop-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.Direction.TopToBottom
            :description: QtMultimedia/QVideoSurfaceFormat-Direction-TopToBottom-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace
        :description: QtMultimedia/QVideoSurfaceFormat-YCbCrColorSpace-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace.YCbCr_BT601
            :description: QtMultimedia/QVideoSurfaceFormat-YCbCrColorSpace-YCbCr_BT601-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace.YCbCr_BT709
            :description: QtMultimedia/QVideoSurfaceFormat-YCbCrColorSpace-YCbCr_BT709-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace.YCbCr_JPEG
            :description: QtMultimedia/QVideoSurfaceFormat-YCbCrColorSpace-YCbCr_JPEG-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace.YCbCr_Undefined
            :description: QtMultimedia/QVideoSurfaceFormat-YCbCrColorSpace-YCbCr_Undefined-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace.YCbCr_xvYCC601
            :description: QtMultimedia/QVideoSurfaceFormat-YCbCrColorSpace-YCbCr_xvYCC601-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace.YCbCr_xvYCC709
            :description: QtMultimedia/QVideoSurfaceFormat-YCbCrColorSpace-YCbCr_xvYCC709-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.__init__
        :description: QtMultimedia/QVideoSurfaceFormat-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.__init__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :description: QtMultimedia/QVideoSurfaceFormat-__init__-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`
            type: :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType` = :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.NoHandle`
        :description: QtMultimedia/QVideoSurfaceFormat-__init__-f-2.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.__eq__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :returns:
            bool
        :description: QtMultimedia/QVideoSurfaceFormat-__eq__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.frameHeight
        :returns:
            int
        :description: QtMultimedia/QVideoSurfaceFormat-frameHeight-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.frameRate
        :returns:
            float
        :description: QtMultimedia/QVideoSurfaceFormat-frameRate-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.frameSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QVideoSurfaceFormat-frameSize-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.frameWidth
        :returns:
            int
        :description: QtMultimedia/QVideoSurfaceFormat-frameWidth-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.handleType
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType`
        :description: QtMultimedia/QVideoSurfaceFormat-handleType-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.isMirrored
        :returns:
            bool
        :description: QtMultimedia/QVideoSurfaceFormat-isMirrored-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.isValid
        :returns:
            bool
        :description: QtMultimedia/QVideoSurfaceFormat-isValid-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.__ne__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :returns:
            bool
        :description: QtMultimedia/QVideoSurfaceFormat-__ne__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.pixelAspectRatio
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QVideoSurfaceFormat-pixelAspectRatio-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.pixelFormat
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`
        :description: QtMultimedia/QVideoSurfaceFormat-pixelFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.property
        :args:
            str
        :returns:
            Any
        :description: QtMultimedia/QVideoSurfaceFormat-property-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.propertyNames
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtMultimedia/QVideoSurfaceFormat-propertyNames-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.scanLineDirection
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.Direction`
        :description: QtMultimedia/QVideoSurfaceFormat-scanLineDirection-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setFrameRate
        :args:
            float
        :description: QtMultimedia/QVideoSurfaceFormat-setFrameRate-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setFrameSize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QVideoSurfaceFormat-setFrameSize-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setFrameSize
        :args:
            int
            int
        :description: QtMultimedia/QVideoSurfaceFormat-setFrameSize-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setMirrored
        :args:
            bool
        :description: QtMultimedia/QVideoSurfaceFormat-setMirrored-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setPixelAspectRatio
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QVideoSurfaceFormat-setPixelAspectRatio-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setPixelAspectRatio
        :args:
            int
            int
        :description: QtMultimedia/QVideoSurfaceFormat-setPixelAspectRatio-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setProperty
        :args:
            str
            Any
        :description: QtMultimedia/QVideoSurfaceFormat-setProperty-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setScanLineDirection
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.Direction`
        :description: QtMultimedia/QVideoSurfaceFormat-setScanLineDirection-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setViewport
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtMultimedia/QVideoSurfaceFormat-setViewport-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.setYCbCrColorSpace
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace`
        :description: QtMultimedia/QVideoSurfaceFormat-setYCbCrColorSpace-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QVideoSurfaceFormat-sizeHint-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.viewport
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtMultimedia/QVideoSurfaceFormat-viewport-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QVideoSurfaceFormat.yCbCrColorSpace
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.YCbCrColorSpace`
        :description: QtMultimedia/QVideoSurfaceFormat-yCbCrColorSpace-f.rst
