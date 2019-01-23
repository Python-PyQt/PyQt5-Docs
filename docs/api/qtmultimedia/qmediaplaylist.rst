:orphan:

.. sip:class:: PyQt5.QtMultimedia.QMediaPlaylist
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject` :sip:ref:`~PyQt5.QtMultimedia.QMediaBindableInterface`
    :description: QtMultimedia/QMediaPlaylist-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaPlaylist.Error
        :description: QtMultimedia/QMediaPlaylist-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.Error.AccessDeniedError
            :description: QtMultimedia/QMediaPlaylist-Error-AccessDeniedError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.Error.FormatError
            :description: QtMultimedia/QMediaPlaylist-Error-FormatError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.Error.FormatNotSupportedError
            :description: QtMultimedia/QMediaPlaylist-Error-FormatNotSupportedError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.Error.NetworkError
            :description: QtMultimedia/QMediaPlaylist-Error-NetworkError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.Error.NoError
            :description: QtMultimedia/QMediaPlaylist-Error-NoError-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode
        :description: QtMultimedia/QMediaPlaylist-PlaybackMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode.CurrentItemInLoop
            :description: QtMultimedia/QMediaPlaylist-PlaybackMode-CurrentItemInLoop-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode.CurrentItemOnce
            :description: QtMultimedia/QMediaPlaylist-PlaybackMode-CurrentItemOnce-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode.Loop
            :description: QtMultimedia/QMediaPlaylist-PlaybackMode-Loop-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode.Random
            :description: QtMultimedia/QMediaPlaylist-PlaybackMode-Random-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode.Sequential
            :description: QtMultimedia/QMediaPlaylist-PlaybackMode-Sequential-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QMediaPlaylist-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.addMedia
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-addMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.addMedia
        :args:
            Iterable[:sip:ref:`~PyQt5.QtMultimedia.QMediaContent`]
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-addMedia-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.clear
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-clear-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.currentIndex
        :returns:
            int
        :description: QtMultimedia/QMediaPlaylist-currentIndex-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.currentMedia
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlaylist-currentMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.Error`
        :description: QtMultimedia/QMediaPlaylist-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.errorString
        :returns:
            str
        :description: QtMultimedia/QMediaPlaylist-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.insertMedia
        :args:
            int
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-insertMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.insertMedia
        :args:
            int
            Iterable[:sip:ref:`~PyQt5.QtMultimedia.QMediaContent`]
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-insertMedia-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.isEmpty
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-isEmpty-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.isReadOnly
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-isReadOnly-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.load
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            format: str = None
        :description: QtMultimedia/QMediaPlaylist-load-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.load
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
            format: str = None
        :description: QtMultimedia/QMediaPlaylist-load-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.load
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
            format: str = None
        :description: QtMultimedia/QMediaPlaylist-load-f-2.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.media
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlaylist-media-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.mediaCount
        :returns:
            int
        :description: QtMultimedia/QMediaPlaylist-mediaCount-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.mediaObject
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
        :description: QtMultimedia/QMediaPlaylist-mediaObject-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.moveMedia
        :args:
            int
            int
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-moveMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.next
        :description: QtMultimedia/QMediaPlaylist-next-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.nextIndex
        :args:
            steps: int = 1
        :returns:
            int
        :description: QtMultimedia/QMediaPlaylist-nextIndex-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.playbackMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode`
        :description: QtMultimedia/QMediaPlaylist-playbackMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.previous
        :description: QtMultimedia/QMediaPlaylist-previous-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.previousIndex
        :args:
            steps: int = 1
        :returns:
            int
        :description: QtMultimedia/QMediaPlaylist-previousIndex-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.removeMedia
        :args:
            int
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-removeMedia-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.removeMedia
        :args:
            int
            int
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-removeMedia-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.save
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
            format: str = None
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-save-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.save
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
            str
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-save-f-1.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.setCurrentIndex
        :args:
            int
        :description: QtMultimedia/QMediaPlaylist-setCurrentIndex-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.setMediaObject
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
        :returns:
            bool
        :description: QtMultimedia/QMediaPlaylist-setMediaObject-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.setPlaybackMode
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode`
        :description: QtMultimedia/QMediaPlaylist-setPlaybackMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaPlaylist.shuffle
        :description: QtMultimedia/QMediaPlaylist-shuffle-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.currentIndexChanged
        :args:
            int
        :description: QtMultimedia/QMediaPlaylist-currentIndexChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.currentMediaChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`
        :description: QtMultimedia/QMediaPlaylist-currentMediaChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.loaded
        :description: QtMultimedia/QMediaPlaylist-loaded-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.loadFailed
        :description: QtMultimedia/QMediaPlaylist-loadFailed-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.mediaAboutToBeInserted
        :args:
            int
            int
        :description: QtMultimedia/QMediaPlaylist-mediaAboutToBeInserted-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.mediaAboutToBeRemoved
        :args:
            int
            int
        :description: QtMultimedia/QMediaPlaylist-mediaAboutToBeRemoved-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.mediaChanged
        :args:
            int
            int
        :description: QtMultimedia/QMediaPlaylist-mediaChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.mediaInserted
        :args:
            int
            int
        :description: QtMultimedia/QMediaPlaylist-mediaInserted-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.mediaRemoved
        :args:
            int
            int
        :description: QtMultimedia/QMediaPlaylist-mediaRemoved-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaPlaylist.playbackModeChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.PlaybackMode`
        :description: QtMultimedia/QMediaPlaylist-playbackModeChanged-s.rst
