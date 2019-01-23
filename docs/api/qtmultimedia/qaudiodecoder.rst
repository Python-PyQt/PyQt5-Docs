:orphan:

.. sip:class:: PyQt5.QtMultimedia.QAudioDecoder
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
    :description: QtMultimedia/QAudioDecoder-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QAudioDecoder.Error
        :description: QtMultimedia/QAudioDecoder-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAudioDecoder.Error.AccessDeniedError
            :description: QtMultimedia/QAudioDecoder-Error-AccessDeniedError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAudioDecoder.Error.FormatError
            :description: QtMultimedia/QAudioDecoder-Error-FormatError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAudioDecoder.Error.NoError
            :description: QtMultimedia/QAudioDecoder-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAudioDecoder.Error.ResourceError
            :description: QtMultimedia/QAudioDecoder-Error-ResourceError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAudioDecoder.Error.ServiceMissingError
            :description: QtMultimedia/QAudioDecoder-Error-ServiceMissingError-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QAudioDecoder.State
        :description: QtMultimedia/QAudioDecoder-State-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAudioDecoder.State.DecodingState
            :description: QtMultimedia/QAudioDecoder-State-DecodingState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAudioDecoder.State.StoppedState
            :description: QtMultimedia/QAudioDecoder-State-StoppedState-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QAudioDecoder-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.audioFormat
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat`
        :description: QtMultimedia/QAudioDecoder-audioFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.bind
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            bool
        :description: QtMultimedia/QAudioDecoder-bind-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.bufferAvailable
        :returns:
            bool
        :description: QtMultimedia/QAudioDecoder-bufferAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.duration
        :returns:
            int
        :description: QtMultimedia/QAudioDecoder-duration-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioDecoder.Error`
        :description: QtMultimedia/QAudioDecoder-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.errorString
        :returns:
            str
        :description: QtMultimedia/QAudioDecoder-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.hasSupport
        :args:
            str
            codecs: Iterable[str] = []
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.SupportEstimate`
        :static:
        :description: QtMultimedia/QAudioDecoder-hasSupport-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.position
        :returns:
            int
        :description: QtMultimedia/QAudioDecoder-position-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.read
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioBuffer`
        :description: QtMultimedia/QAudioDecoder-read-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.setAudioFormat
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat`
        :description: QtMultimedia/QAudioDecoder-setAudioFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.setSourceDevice
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtMultimedia/QAudioDecoder-setSourceDevice-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.setSourceFilename
        :args:
            str
        :description: QtMultimedia/QAudioDecoder-setSourceFilename-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.sourceDevice
        :returns:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtMultimedia/QAudioDecoder-sourceDevice-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.sourceFilename
        :returns:
            str
        :description: QtMultimedia/QAudioDecoder-sourceFilename-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.start
        :description: QtMultimedia/QAudioDecoder-start-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioDecoder.State`
        :description: QtMultimedia/QAudioDecoder-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.stop
        :description: QtMultimedia/QAudioDecoder-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAudioDecoder.unbind
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtMultimedia/QAudioDecoder-unbind-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.bufferAvailableChanged
        :args:
            bool
        :description: QtMultimedia/QAudioDecoder-bufferAvailableChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.bufferReady
        :description: QtMultimedia/QAudioDecoder-bufferReady-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.durationChanged
        :args:
            int
        :description: QtMultimedia/QAudioDecoder-durationChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.error
        :description: QtMultimedia/QAudioDecoder-error-f-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.error
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioDecoder.Error`
        :description: QtMultimedia/QAudioDecoder-error-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.finished
        :description: QtMultimedia/QAudioDecoder-finished-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.formatChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat`
        :description: QtMultimedia/QAudioDecoder-formatChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.positionChanged
        :args:
            int
        :description: QtMultimedia/QAudioDecoder-positionChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.sourceChanged
        :description: QtMultimedia/QAudioDecoder-sourceChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAudioDecoder.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAudioDecoder.State`
        :description: QtMultimedia/QAudioDecoder-stateChanged-s.rst
