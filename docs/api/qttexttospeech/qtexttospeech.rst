:orphan:

.. sip:class:: PyQt5.QtTextToSpeech.QTextToSpeech
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtTextToSpeech/QTextToSpeech-c.rst

    .. sip:enum:: PyQt5.QtTextToSpeech.QTextToSpeech.State
        :description: QtTextToSpeech/QTextToSpeech-State-e.rst

        .. sip:enum-member:: PyQt5.QtTextToSpeech.QTextToSpeech.State.BackendError
            :description: QtTextToSpeech/QTextToSpeech-State-BackendError-v.rst

        .. sip:enum-member:: PyQt5.QtTextToSpeech.QTextToSpeech.State.Paused
            :description: QtTextToSpeech/QTextToSpeech-State-Paused-v.rst

        .. sip:enum-member:: PyQt5.QtTextToSpeech.QTextToSpeech.State.Ready
            :description: QtTextToSpeech/QTextToSpeech-State-Ready-v.rst

        .. sip:enum-member:: PyQt5.QtTextToSpeech.QTextToSpeech.State.Speaking
            :description: QtTextToSpeech/QTextToSpeech-State-Speaking-v.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtTextToSpeech/QTextToSpeech-__init__-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.__init__
        :args:
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtTextToSpeech/QTextToSpeech-__init__-f-1.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.availableEngines
        :returns:
            List[str]
        :static:
        :description: QtTextToSpeech/QTextToSpeech-availableEngines-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.availableLocales
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QLocale`]
        :description: QtTextToSpeech/QTextToSpeech-availableLocales-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.availableVoices
        :returns:
            List[:sip:ref:`~PyQt5.QtTextToSpeech.QVoice`]
        :description: QtTextToSpeech/QTextToSpeech-availableVoices-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.locale
        :returns:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtTextToSpeech/QTextToSpeech-locale-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.pause
        :description: QtTextToSpeech/QTextToSpeech-pause-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.pitch
        :returns:
            float
        :description: QtTextToSpeech/QTextToSpeech-pitch-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.rate
        :returns:
            float
        :description: QtTextToSpeech/QTextToSpeech-rate-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.resume
        :description: QtTextToSpeech/QTextToSpeech-resume-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.say
        :args:
            str
        :description: QtTextToSpeech/QTextToSpeech-say-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtTextToSpeech/QTextToSpeech-setLocale-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.setPitch
        :args:
            float
        :description: QtTextToSpeech/QTextToSpeech-setPitch-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.setRate
        :args:
            float
        :description: QtTextToSpeech/QTextToSpeech-setRate-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.setVoice
        :args:
            :sip:ref:`~PyQt5.QtTextToSpeech.QVoice`
        :description: QtTextToSpeech/QTextToSpeech-setVoice-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.setVolume
        :args:
            float
        :description: QtTextToSpeech/QTextToSpeech-setVolume-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.state
        :returns:
            :sip:ref:`~PyQt5.QtTextToSpeech.QTextToSpeech.State`
        :description: QtTextToSpeech/QTextToSpeech-state-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.stop
        :description: QtTextToSpeech/QTextToSpeech-stop-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.voice
        :returns:
            :sip:ref:`~PyQt5.QtTextToSpeech.QVoice`
        :description: QtTextToSpeech/QTextToSpeech-voice-f.rst

    .. sip:method:: PyQt5.QtTextToSpeech.QTextToSpeech.volume
        :returns:
            float
        :description: QtTextToSpeech/QTextToSpeech-volume-f.rst

    .. sip:signal:: PyQt5.QtTextToSpeech.QTextToSpeech.localeChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtTextToSpeech/QTextToSpeech-localeChanged-s.rst

    .. sip:signal:: PyQt5.QtTextToSpeech.QTextToSpeech.pitchChanged
        :args:
            float
        :description: QtTextToSpeech/QTextToSpeech-pitchChanged-s.rst

    .. sip:signal:: PyQt5.QtTextToSpeech.QTextToSpeech.rateChanged
        :args:
            float
        :description: QtTextToSpeech/QTextToSpeech-rateChanged-s.rst

    .. sip:signal:: PyQt5.QtTextToSpeech.QTextToSpeech.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtTextToSpeech.QTextToSpeech.State`
        :description: QtTextToSpeech/QTextToSpeech-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtTextToSpeech.QTextToSpeech.voiceChanged
        :args:
            :sip:ref:`~PyQt5.QtTextToSpeech.QVoice`
        :description: QtTextToSpeech/QTextToSpeech-voiceChanged-s.rst

    .. sip:signal:: PyQt5.QtTextToSpeech.QTextToSpeech.volumeChanged
        :args:
            float
        :description: QtTextToSpeech/QTextToSpeech-volumeChanged-s.rst

    .. sip:signal:: PyQt5.QtTextToSpeech.QTextToSpeech.volumeChanged
        :args:
            int
        :description: QtTextToSpeech/QTextToSpeech-volumeChanged-s-1.rst
