:orphan:

.. sip:class:: PyQt5.QtMultimedia.QMediaPlayer
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
    :description: QtMultimedia/QMediaPlayer-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaPlayer.Error
        :description: QtMultimedia/QMediaPlayer-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Error.AccessDeniedError
            :description: QtMultimedia/QMediaPlayer-Error-AccessDeniedError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Error.FormatError
            :description: QtMultimedia/QMediaPlayer-Error-FormatError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Error.NetworkError
            :description: QtMultimedia/QMediaPlayer-Error-NetworkError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Error.NoError
            :description: QtMultimedia/QMediaPlayer-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Error.ResourceError
            :description: QtMultimedia/QMediaPlayer-Error-ResourceError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Error.ServiceMissingError
            :description: QtMultimedia/QMediaPlayer-Error-ServiceMissingError-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaPlayer.Flag
        :description: QtMultimedia/QMediaPlayer-Flag-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Flag.LowLatency
            :description: QtMultimedia/QMediaPlayer-Flag-LowLatency-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Flag.StreamPlayback
            :description: QtMultimedia/QMediaPlayer-Flag-StreamPlayback-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.Flag.VideoSurface
            :description: QtMultimedia/QMediaPlayer-Flag-VideoSurface-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus
        :description: QtMultimedia/QMediaPlayer-MediaStatus-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.BufferedMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-BufferedMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.BufferingMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-BufferingMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.EndOfMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-EndOfMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.InvalidMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-InvalidMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.LoadedMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-LoadedMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.LoadingMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-LoadingMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.NoMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-NoMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.StalledMedia
            :description: QtMultimedia/QMediaPlayer-MediaStatus-StalledMedia-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.MediaStatus.UnknownMediaStatus
            :description: QtMultimedia/QMediaPlayer-MediaStatus-UnknownMediaStatus-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaPlayer.State
        :description: QtMultimedia/QMediaPlayer-State-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.State.PausedState
            :description: QtMultimedia/QMediaPlayer-State-PausedState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.State.PlayingState
            :description: QtMultimedia/QMediaPlayer-State-PlayingState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlayer.State.StoppedState
            :description: QtMultimedia/QMediaPlayer-State-StoppedState-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
            flags: Union[:sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Flags`, :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Flag`] = QMediaPlayer.Flags()
        :description: QtMultimedia/QMediaPlayer-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.audioRole
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAudio.Role`
        :description: QtMultimedia/QMediaPlayer-audioRole-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.availability
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.AvailabilityStatus`
        :description: QtMultimedia/QMediaPlayer-availability-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.bind
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayer-bind-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.bufferStatus
        :returns:
            int
        :description: QtMultimedia/QMediaPlayer-bufferStatus-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.currentMedia
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlayer-currentMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.currentNetworkConfiguration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtMultimedia/QMediaPlayer-currentNetworkConfiguration-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.customAudioRole
        :returns:
            str
        :description: QtMultimedia/QMediaPlayer-customAudioRole-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.duration
        :returns:
            int
        :description: QtMultimedia/QMediaPlayer-duration-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Error`
        :description: QtMultimedia/QMediaPlayer-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.errorString
        :returns:
            str
        :description: QtMultimedia/QMediaPlayer-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.hasSupport
        :args:
            str
            codecs: Iterable[str] = []
            flags: Union[:sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Flags`, :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Flag`] = QMediaPlayer.Flags()
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.SupportEstimate`
        :static:
        :description: QtMultimedia/QMediaPlayer-hasSupport-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.isAudioAvailable
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayer-isAudioAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.isMuted
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayer-isMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.isSeekable
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayer-isSeekable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.isVideoAvailable
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayer-isVideoAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.media
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlayer-media-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.mediaStatus
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.MediaStatus`
        :description: QtMultimedia/QMediaPlayer-mediaStatus-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.mediaStream
        :returns:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtMultimedia/QMediaPlayer-mediaStream-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.pause
        :description: QtMultimedia/QMediaPlayer-pause-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.play
        :description: QtMultimedia/QMediaPlayer-play-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.playbackRate
        :returns:
            float
        :description: QtMultimedia/QMediaPlayer-playbackRate-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.playlist
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist`
        :description: QtMultimedia/QMediaPlayer-playlist-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.position
        :returns:
            int
        :description: QtMultimedia/QMediaPlayer-position-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setAudioRole
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudio.Role`
        :description: QtMultimedia/QMediaPlayer-setAudioRole-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setCustomAudioRole
        :args:
            str
        :description: QtMultimedia/QMediaPlayer-setCustomAudioRole-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setMedia
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
            stream: :sip:ref:`~PyQt5.QtCore.QIODevice` = None
        :description: QtMultimedia/QMediaPlayer-setMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setMuted
        :args:
            bool
        :description: QtMultimedia/QMediaPlayer-setMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setNetworkConfigurations
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`]
        :description: QtMultimedia/QMediaPlayer-setNetworkConfigurations-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setPlaybackRate
        :args:
            float
        :description: QtMultimedia/QMediaPlayer-setPlaybackRate-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setPlaylist
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist`
        :description: QtMultimedia/QMediaPlayer-setPlaylist-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setPosition
        :args:
            int
        :description: QtMultimedia/QMediaPlayer-setPosition-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setVideoOutput
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoWidget`
        :description: QtMultimedia/QMediaPlayer-setVideoOutput-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setVideoOutput
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QGraphicsVideoItem`
        :description: QtMultimedia/QMediaPlayer-setVideoOutput-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setVideoOutput
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface`
        :description: QtMultimedia/QMediaPlayer-setVideoOutput-f-2.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setVideoOutput
        :args:
            Iterable[:sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface`]
        :description: QtMultimedia/QMediaPlayer-setVideoOutput-f-3.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.setVolume
        :args:
            int
        :description: QtMultimedia/QMediaPlayer-setVolume-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.State`
        :description: QtMultimedia/QMediaPlayer-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.stop
        :description: QtMultimedia/QMediaPlayer-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.supportedAudioRoles
        :returns:
            List[:sip:ref:`~PyQt5.QtMultimedia.QAudio.Role`]
        :description: QtMultimedia/QMediaPlayer-supportedAudioRoles-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.supportedCustomAudioRoles
        :returns:
            List[str]
        :description: QtMultimedia/QMediaPlayer-supportedCustomAudioRoles-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.supportedMimeTypes
        :args:
            flags: Union[:sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Flags`, :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Flag`] = QMediaPlayer.Flags()
        :returns:
            List[str]
        :static:
        :description: QtMultimedia/QMediaPlayer-supportedMimeTypes-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.unbind
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtMultimedia/QMediaPlayer-unbind-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayer.volume
        :returns:
            int
        :description: QtMultimedia/QMediaPlayer-volume-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.audioAvailableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayer-audioAvailableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.audioRoleChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudio.Role`
        :description: QtMultimedia/QMediaPlayer-audioRoleChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.bufferStatusChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayer-bufferStatusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.currentMediaChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlayer-currentMediaChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.customAudioRoleChanged
        :args:
            str
        :description: QtMultimedia/QMediaPlayer-customAudioRoleChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.durationChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayer-durationChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.error
        :description: QtMultimedia/QMediaPlayer-error-f-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.error
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.Error`
        :description: QtMultimedia/QMediaPlayer-error-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.mediaChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlayer-mediaChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.mediaStatusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.MediaStatus`
        :description: QtMultimedia/QMediaPlayer-mediaStatusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.mutedChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayer-mutedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.networkConfigurationChanged
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtMultimedia/QMediaPlayer-networkConfigurationChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.playbackRateChanged
        :args:
            float
        :description: QtMultimedia/QMediaPlayer-playbackRateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.positionChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayer-positionChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.seekableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayer-seekableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.State`
        :description: QtMultimedia/QMediaPlayer-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.videoAvailableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayer-videoAvailableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayer.volumeChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayer-volumeChanged-s.rst
