:orphan:

.. sip:class:: PyQt5.QtMultimedia.QMediaRecorder
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject` :sip:ref:`~PyQt5.QtMultimedia.QMediaBindableInterface`
    :description: QtMultimedia/QMediaRecorder-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaRecorder.Error
        :description: QtMultimedia/QMediaRecorder-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Error.FormatError
            :description: QtMultimedia/QMediaRecorder-Error-FormatError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Error.NoError
            :description: QtMultimedia/QMediaRecorder-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Error.OutOfSpaceError
            :description: QtMultimedia/QMediaRecorder-Error-OutOfSpaceError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Error.ResourceError
            :description: QtMultimedia/QMediaRecorder-Error-ResourceError-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaRecorder.State
        :description: QtMultimedia/QMediaRecorder-State-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.State.PausedState
            :description: QtMultimedia/QMediaRecorder-State-PausedState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.State.RecordingState
            :description: QtMultimedia/QMediaRecorder-State-RecordingState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.State.StoppedState
            :description: QtMultimedia/QMediaRecorder-State-StoppedState-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaRecorder.Status
        :description: QtMultimedia/QMediaRecorder-Status-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.FinalizingStatus
            :description: QtMultimedia/QMediaRecorder-Status-FinalizingStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.LoadedStatus
            :description: QtMultimedia/QMediaRecorder-Status-LoadedStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.LoadingStatus
            :description: QtMultimedia/QMediaRecorder-Status-LoadingStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.PausedStatus
            :description: QtMultimedia/QMediaRecorder-Status-PausedStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.RecordingStatus
            :description: QtMultimedia/QMediaRecorder-Status-RecordingStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.StartingStatus
            :description: QtMultimedia/QMediaRecorder-Status-StartingStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.UnavailableStatus
            :description: QtMultimedia/QMediaRecorder-Status-UnavailableStatus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaRecorder.Status.UnloadedStatus
            :description: QtMultimedia/QMediaRecorder-Status-UnloadedStatus-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.__init__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QMediaRecorder-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.actualLocation
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtMultimedia/QMediaRecorder-actualLocation-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.audioCodecDescription
        :args:
            str
        :returns:
            str
        :description: QtMultimedia/QMediaRecorder-audioCodecDescription-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.audioSettings
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioEncoderSettings`
        :description: QtMultimedia/QMediaRecorder-audioSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.availability
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.AvailabilityStatus`
        :description: QtMultimedia/QMediaRecorder-availability-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.availableMetaData
        :returns:
            List[str]
        :description: QtMultimedia/QMediaRecorder-availableMetaData-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.containerDescription
        :args:
            str
        :returns:
            str
        :description: QtMultimedia/QMediaRecorder-containerDescription-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.containerFormat
        :returns:
            str
        :description: QtMultimedia/QMediaRecorder-containerFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.duration
        :returns:
            int
        :description: QtMultimedia/QMediaRecorder-duration-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.Error`
        :description: QtMultimedia/QMediaRecorder-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.errorString
        :returns:
            str
        :description: QtMultimedia/QMediaRecorder-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.isAvailable
        :returns:
            bool
        :description: QtMultimedia/QMediaRecorder-isAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.isMetaDataAvailable
        :returns:
            bool
        :description: QtMultimedia/QMediaRecorder-isMetaDataAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.isMetaDataWritable
        :returns:
            bool
        :description: QtMultimedia/QMediaRecorder-isMetaDataWritable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.isMuted
        :returns:
            bool
        :description: QtMultimedia/QMediaRecorder-isMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.mediaObject
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
        :description: QtMultimedia/QMediaRecorder-mediaObject-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.metaData
        :args:
            str
        :returns:
            Any
        :description: QtMultimedia/QMediaRecorder-metaData-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.outputLocation
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtMultimedia/QMediaRecorder-outputLocation-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.pause
        :description: QtMultimedia/QMediaRecorder-pause-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.record
        :description: QtMultimedia/QMediaRecorder-record-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setAudioSettings
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioEncoderSettings`
        :description: QtMultimedia/QMediaRecorder-setAudioSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setContainerFormat
        :args:
            str
        :description: QtMultimedia/QMediaRecorder-setContainerFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setEncodingSettings
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioEncoderSettings`
            video: :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings` = QVideoEncoderSettings()
            container: str = ''
        :description: QtMultimedia/QMediaRecorder-setEncodingSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setMediaObject
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
        :returns:
            bool
        :description: QtMultimedia/QMediaRecorder-setMediaObject-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setMetaData
        :args:
            str
            Any
        :description: QtMultimedia/QMediaRecorder-setMetaData-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setMuted
        :args:
            bool
        :description: QtMultimedia/QMediaRecorder-setMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setOutputLocation
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            bool
        :description: QtMultimedia/QMediaRecorder-setOutputLocation-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setVideoSettings
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings`
        :description: QtMultimedia/QMediaRecorder-setVideoSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.setVolume
        :args:
            float
        :description: QtMultimedia/QMediaRecorder-setVolume-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.State`
        :description: QtMultimedia/QMediaRecorder-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.status
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.Status`
        :description: QtMultimedia/QMediaRecorder-status-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.stop
        :description: QtMultimedia/QMediaRecorder-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.supportedAudioCodecs
        :returns:
            List[str]
        :description: QtMultimedia/QMediaRecorder-supportedAudioCodecs-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.supportedAudioSampleRates
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QAudioEncoderSettings` = QAudioEncoderSettings()
        :returns:
            List[int]
            bool
        :description: QtMultimedia/QMediaRecorder-supportedAudioSampleRates-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.supportedContainers
        :returns:
            List[str]
        :description: QtMultimedia/QMediaRecorder-supportedContainers-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.supportedFrameRates
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings` = QVideoEncoderSettings()
        :returns:
            List[float]
            bool
        :description: QtMultimedia/QMediaRecorder-supportedFrameRates-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.supportedResolutions
        :args:
            settings: :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings` = QVideoEncoderSettings()
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QSize`]
            bool
        :description: QtMultimedia/QMediaRecorder-supportedResolutions-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.supportedVideoCodecs
        :returns:
            List[str]
        :description: QtMultimedia/QMediaRecorder-supportedVideoCodecs-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.videoCodecDescription
        :args:
            str
        :returns:
            str
        :description: QtMultimedia/QMediaRecorder-videoCodecDescription-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.videoSettings
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings`
        :description: QtMultimedia/QMediaRecorder-videoSettings-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaRecorder.volume
        :returns:
            float
        :description: QtMultimedia/QMediaRecorder-volume-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.actualLocationChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtMultimedia/QMediaRecorder-actualLocationChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.availabilityChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.AvailabilityStatus`
        :description: QtMultimedia/QMediaRecorder-availabilityChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.availabilityChanged
        :args:
            bool
        :description: QtMultimedia/QMediaRecorder-availabilityChanged-s-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.durationChanged
        :args:
            int
        :description: QtMultimedia/QMediaRecorder-durationChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.error
        :description: QtMultimedia/QMediaRecorder-error-f-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.error
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.Error`
        :description: QtMultimedia/QMediaRecorder-error-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.metaDataAvailableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaRecorder-metaDataAvailableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.metaDataChanged
        :args:
            str
            Any
        :description: QtMultimedia/QMediaRecorder-metaDataChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.metaDataChanged
        :description: QtMultimedia/QMediaRecorder-metaDataChanged-s-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.metaDataWritableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaRecorder-metaDataWritableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.mutedChanged
        :args:
            bool
        :description: QtMultimedia/QMediaRecorder-mutedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.State`
        :description: QtMultimedia/QMediaRecorder-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.statusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.Status`
        :description: QtMultimedia/QMediaRecorder-statusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaRecorder.volumeChanged
        :args:
            float
        :description: QtMultimedia/QMediaRecorder-volumeChanged-s.rst
