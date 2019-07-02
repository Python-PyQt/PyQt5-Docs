:orphan:

.. sip:class:: PyQt5.QtMultimedia.QSoundEffect
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtMultimedia/QSoundEffect-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QSoundEffect.Loop
        :description: QtMultimedia/QSoundEffect-Loop-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QSoundEffect.Loop.Infinite
            :description: QtMultimedia/QSoundEffect-Loop-Infinite-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QSoundEffect.Status
        :description: QtMultimedia/QSoundEffect-Status-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QSoundEffect.Status.Error
            :description: QtMultimedia/QSoundEffect-Status-Error-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QSoundEffect.Status.Loading
            :description: QtMultimedia/QSoundEffect-Status-Loading-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QSoundEffect.Status.Null
            :description: QtMultimedia/QSoundEffect-Status-Null-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QSoundEffect.Status.Ready
            :description: QtMultimedia/QSoundEffect-Status-Ready-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QSoundEffect-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.__init__
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QSoundEffect-__init__-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.category
        :returns:
            str
        :description: QtMultimedia/QSoundEffect-category-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.isLoaded
        :returns:
            bool
        :description: QtMultimedia/QSoundEffect-isLoaded-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.isMuted
        :returns:
            bool
        :description: QtMultimedia/QSoundEffect-isMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.isPlaying
        :returns:
            bool
        :description: QtMultimedia/QSoundEffect-isPlaying-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.loopCount
        :returns:
            int
        :description: QtMultimedia/QSoundEffect-loopCount-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.loopsRemaining
        :returns:
            int
        :description: QtMultimedia/QSoundEffect-loopsRemaining-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.play
        :description: QtMultimedia/QSoundEffect-play-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.setCategory
        :args:
            str
        :description: QtMultimedia/QSoundEffect-setCategory-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.setLoopCount
        :args:
            int
        :description: QtMultimedia/QSoundEffect-setLoopCount-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.setMuted
        :args:
            bool
        :description: QtMultimedia/QSoundEffect-setMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.setSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtMultimedia/QSoundEffect-setSource-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.setVolume
        :args:
            float
        :description: QtMultimedia/QSoundEffect-setVolume-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.source
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtMultimedia/QSoundEffect-source-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.status
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QSoundEffect.Status`
        :description: QtMultimedia/QSoundEffect-status-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.stop
        :description: QtMultimedia/QSoundEffect-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.supportedMimeTypes
        :returns:
            List[str]
        :static:
        :description: QtMultimedia/QSoundEffect-supportedMimeTypes-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QSoundEffect.volume
        :returns:
            float
        :description: QtMultimedia/QSoundEffect-volume-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.categoryChanged
        :description: QtMultimedia/QSoundEffect-categoryChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.loadedChanged
        :description: QtMultimedia/QSoundEffect-loadedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.loopCountChanged
        :description: QtMultimedia/QSoundEffect-loopCountChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.loopsRemainingChanged
        :description: QtMultimedia/QSoundEffect-loopsRemainingChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.mutedChanged
        :description: QtMultimedia/QSoundEffect-mutedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.playingChanged
        :description: QtMultimedia/QSoundEffect-playingChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.sourceChanged
        :description: QtMultimedia/QSoundEffect-sourceChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.statusChanged
        :description: QtMultimedia/QSoundEffect-statusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QSoundEffect.volumeChanged
        :description: QtMultimedia/QSoundEffect-volumeChanged-s.rst
