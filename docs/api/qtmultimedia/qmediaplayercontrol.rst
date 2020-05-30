:orphan:

.. sip:class:: PyQt5.QtMultimedia.QMediaPlayerControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QMediaPlayerControl-c.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QMediaPlayerControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.availablePlaybackRanges
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange`
        :description: QtMultimedia/QMediaPlayerControl-availablePlaybackRanges-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.bufferStatus
        :returns:
            int
        :description: QtMultimedia/QMediaPlayerControl-bufferStatus-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.duration
        :returns:
            int
        :description: QtMultimedia/QMediaPlayerControl-duration-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.isAudioAvailable
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayerControl-isAudioAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.isMuted
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayerControl-isMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.isSeekable
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayerControl-isSeekable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.isVideoAvailable
        :returns:
            bool
        :description: QtMultimedia/QMediaPlayerControl-isVideoAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.media
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlayerControl-media-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.mediaStatus
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.MediaStatus`
        :description: QtMultimedia/QMediaPlayerControl-mediaStatus-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.mediaStream
        :returns:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtMultimedia/QMediaPlayerControl-mediaStream-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.pause
        :description: QtMultimedia/QMediaPlayerControl-pause-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.play
        :description: QtMultimedia/QMediaPlayerControl-play-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.playbackRate
        :returns:
            float
        :description: QtMultimedia/QMediaPlayerControl-playbackRate-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.position
        :returns:
            int
        :description: QtMultimedia/QMediaPlayerControl-position-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.setMedia
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtMultimedia/QMediaPlayerControl-setMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.setMuted
        :args:
            bool
        :description: QtMultimedia/QMediaPlayerControl-setMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.setPlaybackRate
        :args:
            float
        :description: QtMultimedia/QMediaPlayerControl-setPlaybackRate-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.setPosition
        :args:
            int
        :description: QtMultimedia/QMediaPlayerControl-setPosition-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.setVolume
        :args:
            int
        :description: QtMultimedia/QMediaPlayerControl-setVolume-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.State`
        :description: QtMultimedia/QMediaPlayerControl-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.stop
        :description: QtMultimedia/QMediaPlayerControl-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlayerControl.volume
        :returns:
            int
        :description: QtMultimedia/QMediaPlayerControl-volume-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.audioAvailableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayerControl-audioAvailableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.availablePlaybackRangesChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange`
        :description: QtMultimedia/QMediaPlayerControl-availablePlaybackRangesChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.bufferStatusChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayerControl-bufferStatusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.durationChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayerControl-durationChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.error
        :args:
            int
            str
        :description: QtMultimedia/QMediaPlayerControl-error-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.mediaChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlayerControl-mediaChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.mediaStatusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.MediaStatus`
        :description: QtMultimedia/QMediaPlayerControl-mediaStatusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.mutedChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayerControl-mutedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.playbackRateChanged
        :args:
            float
        :description: QtMultimedia/QMediaPlayerControl-playbackRateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.positionChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayerControl-positionChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.seekableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayerControl-seekableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer.State`
        :description: QtMultimedia/QMediaPlayerControl-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.videoAvailableChanged
        :args:
            bool
        :description: QtMultimedia/QMediaPlayerControl-videoAvailableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlayerControl.volumeChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlayerControl-volumeChanged-s.rst
