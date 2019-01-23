:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCamera
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
    :description: QtMultimedia/QCamera-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.CaptureMode
        :description: QtMultimedia/QCamera-CaptureMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.CaptureMode.CaptureStillImage
            :description: QtMultimedia/QCamera-CaptureMode-CaptureStillImage-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.CaptureMode.CaptureVideo
            :description: QtMultimedia/QCamera-CaptureMode-CaptureVideo-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.CaptureMode.CaptureViewfinder
            :description: QtMultimedia/QCamera-CaptureMode-CaptureViewfinder-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.Error
        :description: QtMultimedia/QCamera-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Error.CameraError
            :description: QtMultimedia/QCamera-Error-CameraError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Error.InvalidRequestError
            :description: QtMultimedia/QCamera-Error-InvalidRequestError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Error.NoError
            :description: QtMultimedia/QCamera-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Error.NotSupportedFeatureError
            :description: QtMultimedia/QCamera-Error-NotSupportedFeatureError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Error.ServiceMissingError
            :description: QtMultimedia/QCamera-Error-ServiceMissingError-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.LockChangeReason
        :description: QtMultimedia/QCamera-LockChangeReason-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockChangeReason.LockAcquired
            :description: QtMultimedia/QCamera-LockChangeReason-LockAcquired-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockChangeReason.LockFailed
            :description: QtMultimedia/QCamera-LockChangeReason-LockFailed-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockChangeReason.LockLost
            :description: QtMultimedia/QCamera-LockChangeReason-LockLost-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockChangeReason.LockTemporaryLost
            :description: QtMultimedia/QCamera-LockChangeReason-LockTemporaryLost-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockChangeReason.UserRequest
            :description: QtMultimedia/QCamera-LockChangeReason-UserRequest-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.LockStatus
        :description: QtMultimedia/QCamera-LockStatus-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockStatus.Locked
            :description: QtMultimedia/QCamera-LockStatus-Locked-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockStatus.Searching
            :description: QtMultimedia/QCamera-LockStatus-Searching-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockStatus.Unlocked
            :description: QtMultimedia/QCamera-LockStatus-Unlocked-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.LockType
        :description: QtMultimedia/QCamera-LockType-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockType.LockExposure
            :description: QtMultimedia/QCamera-LockType-LockExposure-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockType.LockFocus
            :description: QtMultimedia/QCamera-LockType-LockFocus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockType.LockWhiteBalance
            :description: QtMultimedia/QCamera-LockType-LockWhiteBalance-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.LockType.NoLock
            :description: QtMultimedia/QCamera-LockType-NoLock-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.Position
        :description: QtMultimedia/QCamera-Position-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Position.BackFace
            :description: QtMultimedia/QCamera-Position-BackFace-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Position.FrontFace
            :description: QtMultimedia/QCamera-Position-FrontFace-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Position.UnspecifiedPosition
            :description: QtMultimedia/QCamera-Position-UnspecifiedPosition-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.State
        :description: QtMultimedia/QCamera-State-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.State.ActiveState
            :description: QtMultimedia/QCamera-State-ActiveState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.State.LoadedState
            :description: QtMultimedia/QCamera-State-LoadedState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.State.UnloadedState
            :description: QtMultimedia/QCamera-State-UnloadedState-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCamera.Status
        :description: QtMultimedia/QCamera-Status-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.ActiveStatus
            :description: QtMultimedia/QCamera-Status-ActiveStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.LoadedStatus
            :description: QtMultimedia/QCamera-Status-LoadedStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.LoadingStatus
            :description: QtMultimedia/QCamera-Status-LoadingStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.StandbyStatus
            :description: QtMultimedia/QCamera-Status-StandbyStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.StartingStatus
            :description: QtMultimedia/QCamera-Status-StartingStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.StoppingStatus
            :description: QtMultimedia/QCamera-Status-StoppingStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.UnavailableStatus
            :description: QtMultimedia/QCamera-Status-UnavailableStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.UnloadedStatus
            :description: QtMultimedia/QCamera-Status-UnloadedStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCamera.Status.UnloadingStatus
            :description: QtMultimedia/QCamera-Status-UnloadingStatus-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCamera-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCamera-__init__-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.__init__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCamera-__init__-f-2.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.__init__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Position`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCamera-__init__-f-3.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.availability
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.AvailabilityStatus`
        :description: QtMultimedia/QCamera-availability-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.availableDevices
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :static:
        :description: QtMultimedia/QCamera-availableDevices-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.captureMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`
        :description: QtMultimedia/QCamera-captureMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.deviceDescription
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            str
        :static:
        :description: QtMultimedia/QCamera-deviceDescription-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Error`
        :description: QtMultimedia/QCamera-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.errorString
        :returns:
            str
        :description: QtMultimedia/QCamera-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.exposure
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraExposure`
        :description: QtMultimedia/QCamera-exposure-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.focus
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus`
        :description: QtMultimedia/QCamera-focus-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.imageProcessing
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraImageProcessing`
        :description: QtMultimedia/QCamera-imageProcessing-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.isCaptureModeSupported
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureMode`]
        :returns:
            bool
        :description: QtMultimedia/QCamera-isCaptureModeSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.load
        :description: QtMultimedia/QCamera-load-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.lockStatus
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockStatus`
        :description: QtMultimedia/QCamera-lockStatus-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.lockStatus
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockStatus`
        :description: QtMultimedia/QCamera-lockStatus-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.requestedLocks
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockTypes`
        :description: QtMultimedia/QCamera-requestedLocks-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.searchAndLock
        :description: QtMultimedia/QCamera-searchAndLock-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.searchAndLock
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.LockTypes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`]
        :description: QtMultimedia/QCamera-searchAndLock-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.setCaptureMode
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureMode`]
        :description: QtMultimedia/QCamera-setCaptureMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.setViewfinder
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoWidget`
        :description: QtMultimedia/QCamera-setViewfinder-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.setViewfinder
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QGraphicsVideoItem`
        :description: QtMultimedia/QCamera-setViewfinder-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.setViewfinder
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface`
        :description: QtMultimedia/QCamera-setViewfinder-f-2.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.setViewfinderSettings
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings`
        :description: QtMultimedia/QCamera-setViewfinderSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.start
        :description: QtMultimedia/QCamera-start-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.State`
        :description: QtMultimedia/QCamera-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.status
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Status`
        :description: QtMultimedia/QCamera-status-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.stop
        :description: QtMultimedia/QCamera-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.supportedLocks
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockTypes`
        :description: QtMultimedia/QCamera-supportedLocks-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.supportedViewfinderFrameRateRanges
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings` = QCameraViewfinderSettings()
        :returns:
            List[:sip:ref:`~PyQt5.QtMultimedia.QCamera.FrameRateRange`]
        :description: QtMultimedia/QCamera-supportedViewfinderFrameRateRanges-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.supportedViewfinderPixelFormats
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings` = QCameraViewfinderSettings()
        :returns:
            List[:sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`]
        :description: QtMultimedia/QCamera-supportedViewfinderPixelFormats-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.supportedViewfinderResolutions
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings` = QCameraViewfinderSettings()
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QSize`]
        :description: QtMultimedia/QCamera-supportedViewfinderResolutions-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.supportedViewfinderSettings
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings` = QCameraViewfinderSettings()
        :returns:
            List[:sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings`]
        :description: QtMultimedia/QCamera-supportedViewfinderSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.unload
        :description: QtMultimedia/QCamera-unload-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.unlock
        :description: QtMultimedia/QCamera-unlock-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.unlock
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.LockTypes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`]
        :description: QtMultimedia/QCamera-unlock-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QCamera.viewfinderSettings
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings`
        :description: QtMultimedia/QCamera-viewfinderSettings-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.captureModeChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureMode`]
        :description: QtMultimedia/QCamera-captureModeChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.error
        :description: QtMultimedia/QCamera-error-f-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.error
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Error`
        :description: QtMultimedia/QCamera-error-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.locked
        :description: QtMultimedia/QCamera-locked-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.lockFailed
        :description: QtMultimedia/QCamera-lockFailed-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.lockStatusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockStatus`
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockChangeReason`
        :description: QtMultimedia/QCamera-lockStatusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.lockStatusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockStatus`
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockChangeReason`
        :description: QtMultimedia/QCamera-lockStatusChanged-s-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.State`
        :description: QtMultimedia/QCamera-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCamera.statusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Status`
        :description: QtMultimedia/QCamera-statusChanged-s.rst
