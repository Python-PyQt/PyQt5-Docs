:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCameraImageCapture
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject` :sip:ref:`~PyQt5.QtMultimedia.QMediaBindableInterface`
    :description: QtMultimedia/QCameraImageCapture-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestination
        :description: QtMultimedia/QCameraImageCapture-CaptureDestination-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestination.CaptureToBuffer
            :description: QtMultimedia/QCameraImageCapture-CaptureDestination-CaptureToBuffer-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestination.CaptureToFile
            :description: QtMultimedia/QCameraImageCapture-CaptureDestination-CaptureToFile-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraImageCapture.DriveMode
        :description: QtMultimedia/QCameraImageCapture-DriveMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.DriveMode.SingleImageCapture
            :description: QtMultimedia/QCameraImageCapture-DriveMode-SingleImageCapture-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraImageCapture.Error
        :description: QtMultimedia/QCameraImageCapture-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.Error.FormatError
            :description: QtMultimedia/QCameraImageCapture-Error-FormatError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.Error.NoError
            :description: QtMultimedia/QCameraImageCapture-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.Error.NotReadyError
            :description: QtMultimedia/QCameraImageCapture-Error-NotReadyError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.Error.NotSupportedFeatureError
            :description: QtMultimedia/QCameraImageCapture-Error-NotSupportedFeatureError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.Error.OutOfSpaceError
            :description: QtMultimedia/QCameraImageCapture-Error-OutOfSpaceError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraImageCapture.Error.ResourceError
            :description: QtMultimedia/QCameraImageCapture-Error-ResourceError-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.__init__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCameraImageCapture-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.availability
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.AvailabilityStatus`
        :description: QtMultimedia/QCameraImageCapture-availability-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.bufferFormat
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`
        :description: QtMultimedia/QCameraImageCapture-bufferFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.cancelCapture
        :description: QtMultimedia/QCameraImageCapture-cancelCapture-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.capture
        :args:
            file: str = ''
        :returns:
            int
        :description: QtMultimedia/QCameraImageCapture-capture-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.captureDestination
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestinations`
        :description: QtMultimedia/QCameraImageCapture-captureDestination-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.encodingSettings
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QImageEncoderSettings`
        :description: QtMultimedia/QCameraImageCapture-encodingSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.Error`
        :description: QtMultimedia/QCameraImageCapture-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.errorString
        :returns:
            str
        :description: QtMultimedia/QCameraImageCapture-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.imageCodecDescription
        :args:
            str
        :returns:
            str
        :description: QtMultimedia/QCameraImageCapture-imageCodecDescription-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.isAvailable
        :returns:
            bool
        :description: QtMultimedia/QCameraImageCapture-isAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.isCaptureDestinationSupported
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestinations`, :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestination`]
        :returns:
            bool
        :description: QtMultimedia/QCameraImageCapture-isCaptureDestinationSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.isReadyForCapture
        :returns:
            bool
        :description: QtMultimedia/QCameraImageCapture-isReadyForCapture-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.mediaObject
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
        :description: QtMultimedia/QCameraImageCapture-mediaObject-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.setBufferFormat
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`
        :description: QtMultimedia/QCameraImageCapture-setBufferFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.setCaptureDestination
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestinations`, :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestination`]
        :description: QtMultimedia/QCameraImageCapture-setCaptureDestination-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.setEncodingSettings
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QImageEncoderSettings`
        :description: QtMultimedia/QCameraImageCapture-setEncodingSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.setMediaObject
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
        :returns:
            bool
        :description: QtMultimedia/QCameraImageCapture-setMediaObject-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.supportedBufferFormats
        :returns:
            List[:sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`]
        :description: QtMultimedia/QCameraImageCapture-supportedBufferFormats-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.supportedImageCodecs
        :returns:
            List[str]
        :description: QtMultimedia/QCameraImageCapture-supportedImageCodecs-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCapture.supportedResolutions
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QImageEncoderSettings` = QImageEncoderSettings()
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QSize`]
            bool
        :description: QtMultimedia/QCameraImageCapture-supportedResolutions-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.bufferFormatChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`
        :description: QtMultimedia/QCameraImageCapture-bufferFormatChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.captureDestinationChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestinations`, :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.CaptureDestination`]
        :description: QtMultimedia/QCameraImageCapture-captureDestinationChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.error
        :description: QtMultimedia/QCameraImageCapture-error-f-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.error
        :args:
            int
            :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.Error`
            str
        :description: QtMultimedia/QCameraImageCapture-error-f-2.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.imageAvailable
        :args:
            int
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame`
        :description: QtMultimedia/QCameraImageCapture-imageAvailable-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.imageCaptured
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtMultimedia/QCameraImageCapture-imageCaptured-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.imageExposed
        :args:
            int
        :description: QtMultimedia/QCameraImageCapture-imageExposed-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.imageMetadataAvailable
        :args:
            int
            str
            Any
        :description: QtMultimedia/QCameraImageCapture-imageMetadataAvailable-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.imageSaved
        :args:
            int
            str
        :description: QtMultimedia/QCameraImageCapture-imageSaved-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCapture.readyForCaptureChanged
        :args:
            bool
        :description: QtMultimedia/QCameraImageCapture-readyForCaptureChanged-s.rst
