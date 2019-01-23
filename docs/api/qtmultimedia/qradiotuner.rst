:orphan:

.. sip:class:: PyQt5.QtMultimedia.QRadioTuner
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`
    :description: QtMultimedia/QRadioTuner-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QRadioTuner.Band
        :description: QtMultimedia/QRadioTuner-Band-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Band.AM
            :description: QtMultimedia/QRadioTuner-Band-AM-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Band.FM
            :description: QtMultimedia/QRadioTuner-Band-FM-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Band.FM2
            :description: QtMultimedia/QRadioTuner-Band-FM2-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Band.LW
            :description: QtMultimedia/QRadioTuner-Band-LW-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Band.SW
            :description: QtMultimedia/QRadioTuner-Band-SW-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QRadioTuner.Error
        :description: QtMultimedia/QRadioTuner-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Error.NoError
            :description: QtMultimedia/QRadioTuner-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Error.OpenError
            :description: QtMultimedia/QRadioTuner-Error-OpenError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Error.OutOfRangeError
            :description: QtMultimedia/QRadioTuner-Error-OutOfRangeError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.Error.ResourceError
            :description: QtMultimedia/QRadioTuner-Error-ResourceError-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QRadioTuner.SearchMode
        :description: QtMultimedia/QRadioTuner-SearchMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.SearchMode.SearchFast
            :description: QtMultimedia/QRadioTuner-SearchMode-SearchFast-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.SearchMode.SearchGetStationId
            :description: QtMultimedia/QRadioTuner-SearchMode-SearchGetStationId-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QRadioTuner.State
        :description: QtMultimedia/QRadioTuner-State-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.State.ActiveState
            :description: QtMultimedia/QRadioTuner-State-ActiveState-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.State.StoppedState
            :description: QtMultimedia/QRadioTuner-State-StoppedState-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QRadioTuner.StereoMode
        :description: QtMultimedia/QRadioTuner-StereoMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.StereoMode.Auto
            :description: QtMultimedia/QRadioTuner-StereoMode-Auto-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.StereoMode.ForceMono
            :description: QtMultimedia/QRadioTuner-StereoMode-ForceMono-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QRadioTuner.StereoMode.ForceStereo
            :description: QtMultimedia/QRadioTuner-StereoMode-ForceStereo-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QRadioTuner-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.availability
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMultimedia.AvailabilityStatus`
        :description: QtMultimedia/QRadioTuner-availability-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.band
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :description: QtMultimedia/QRadioTuner-band-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.cancelSearch
        :description: QtMultimedia/QRadioTuner-cancelSearch-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Error`
        :description: QtMultimedia/QRadioTuner-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.errorString
        :returns:
            str
        :description: QtMultimedia/QRadioTuner-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.frequency
        :returns:
            int
        :description: QtMultimedia/QRadioTuner-frequency-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.frequencyRange
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :returns:
            Tuple[int, int]
        :description: QtMultimedia/QRadioTuner-frequencyRange-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.frequencyStep
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :returns:
            int
        :description: QtMultimedia/QRadioTuner-frequencyStep-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.isAntennaConnected
        :returns:
            bool
        :description: QtMultimedia/QRadioTuner-isAntennaConnected-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.isBandSupported
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :returns:
            bool
        :description: QtMultimedia/QRadioTuner-isBandSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.isMuted
        :returns:
            bool
        :description: QtMultimedia/QRadioTuner-isMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.isSearching
        :returns:
            bool
        :description: QtMultimedia/QRadioTuner-isSearching-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.isStereo
        :returns:
            bool
        :description: QtMultimedia/QRadioTuner-isStereo-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.radioData
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioData`
        :description: QtMultimedia/QRadioTuner-radioData-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.searchAllStations
        :args:
            searchMode: :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.SearchMode` = :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.SearchMode.SearchFast`
        :description: QtMultimedia/QRadioTuner-searchAllStations-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.searchBackward
        :description: QtMultimedia/QRadioTuner-searchBackward-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.searchForward
        :description: QtMultimedia/QRadioTuner-searchForward-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.setBand
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :description: QtMultimedia/QRadioTuner-setBand-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.setFrequency
        :args:
            int
        :description: QtMultimedia/QRadioTuner-setFrequency-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.setMuted
        :args:
            bool
        :description: QtMultimedia/QRadioTuner-setMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.setStereoMode
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.StereoMode`
        :description: QtMultimedia/QRadioTuner-setStereoMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.setVolume
        :args:
            int
        :description: QtMultimedia/QRadioTuner-setVolume-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.signalStrength
        :returns:
            int
        :description: QtMultimedia/QRadioTuner-signalStrength-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.start
        :description: QtMultimedia/QRadioTuner-start-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.State`
        :description: QtMultimedia/QRadioTuner-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.stereoMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.StereoMode`
        :description: QtMultimedia/QRadioTuner-stereoMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.stop
        :description: QtMultimedia/QRadioTuner-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTuner.volume
        :returns:
            int
        :description: QtMultimedia/QRadioTuner-volume-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.antennaConnectedChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTuner-antennaConnectedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.bandChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :description: QtMultimedia/QRadioTuner-bandChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.error
        :description: QtMultimedia/QRadioTuner-error-f-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.error
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Error`
        :description: QtMultimedia/QRadioTuner-error-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.frequencyChanged
        :args:
            int
        :description: QtMultimedia/QRadioTuner-frequencyChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.mutedChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTuner-mutedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.searchingChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTuner-searchingChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.signalStrengthChanged
        :args:
            int
        :description: QtMultimedia/QRadioTuner-signalStrengthChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.State`
        :description: QtMultimedia/QRadioTuner-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.stationFound
        :args:
            int
            str
        :description: QtMultimedia/QRadioTuner-stationFound-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.stereoStatusChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTuner-stereoStatusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTuner.volumeChanged
        :args:
            int
        :description: QtMultimedia/QRadioTuner-volumeChanged-s.rst
