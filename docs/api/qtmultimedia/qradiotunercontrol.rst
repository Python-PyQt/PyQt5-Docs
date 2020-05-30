:orphan:

.. sip:class:: PyQt5.QtMultimedia.QRadioTunerControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QRadioTunerControl-c.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QRadioTunerControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.band
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :description: QtMultimedia/QRadioTunerControl-band-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.cancelSearch
        :description: QtMultimedia/QRadioTunerControl-cancelSearch-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Error`
        :description: QtMultimedia/QRadioTunerControl-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.errorString
        :returns:
            str
        :description: QtMultimedia/QRadioTunerControl-errorString-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.frequency
        :returns:
            int
        :description: QtMultimedia/QRadioTunerControl-frequency-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.frequencyRange
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :returns:
            Tuple[int, int]
        :description: QtMultimedia/QRadioTunerControl-frequencyRange-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.frequencyStep
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :returns:
            int
        :description: QtMultimedia/QRadioTunerControl-frequencyStep-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.isAntennaConnected
        :returns:
            bool
        :description: QtMultimedia/QRadioTunerControl-isAntennaConnected-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.isBandSupported
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :returns:
            bool
        :description: QtMultimedia/QRadioTunerControl-isBandSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.isMuted
        :returns:
            bool
        :description: QtMultimedia/QRadioTunerControl-isMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.isSearching
        :returns:
            bool
        :description: QtMultimedia/QRadioTunerControl-isSearching-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.isStereo
        :returns:
            bool
        :description: QtMultimedia/QRadioTunerControl-isStereo-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.searchAllStations
        :args:
            searchMode: :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.SearchMode` = :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.SearchMode.SearchFast`
        :description: QtMultimedia/QRadioTunerControl-searchAllStations-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.searchBackward
        :description: QtMultimedia/QRadioTunerControl-searchBackward-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.searchForward
        :description: QtMultimedia/QRadioTunerControl-searchForward-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.setBand
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :description: QtMultimedia/QRadioTunerControl-setBand-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.setFrequency
        :args:
            int
        :description: QtMultimedia/QRadioTunerControl-setFrequency-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.setMuted
        :args:
            bool
        :description: QtMultimedia/QRadioTunerControl-setMuted-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.setStereoMode
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.StereoMode`
        :description: QtMultimedia/QRadioTunerControl-setStereoMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.setVolume
        :args:
            int
        :description: QtMultimedia/QRadioTunerControl-setVolume-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.signalStrength
        :returns:
            int
        :description: QtMultimedia/QRadioTunerControl-signalStrength-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.start
        :description: QtMultimedia/QRadioTunerControl-start-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.State`
        :description: QtMultimedia/QRadioTunerControl-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.stereoMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.StereoMode`
        :description: QtMultimedia/QRadioTunerControl-stereoMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.stop
        :description: QtMultimedia/QRadioTunerControl-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QRadioTunerControl.volume
        :returns:
            int
        :description: QtMultimedia/QRadioTunerControl-volume-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.antennaConnectedChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTunerControl-antennaConnectedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.bandChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Band`
        :description: QtMultimedia/QRadioTunerControl-bandChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.error
        :description: QtMultimedia/QRadioTunerControl-error-f-1.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.error
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.Error`
        :description: QtMultimedia/QRadioTunerControl-error-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.frequencyChanged
        :args:
            int
        :description: QtMultimedia/QRadioTunerControl-frequencyChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.mutedChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTunerControl-mutedChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.searchingChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTunerControl-searchingChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.signalStrengthChanged
        :args:
            int
        :description: QtMultimedia/QRadioTunerControl-signalStrengthChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.State`
        :description: QtMultimedia/QRadioTunerControl-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.stationFound
        :args:
            int
            str
        :description: QtMultimedia/QRadioTunerControl-stationFound-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.stereoStatusChanged
        :args:
            bool
        :description: QtMultimedia/QRadioTunerControl-stereoStatusChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QRadioTunerControl.volumeChanged
        :args:
            int
        :description: QtMultimedia/QRadioTunerControl-volumeChanged-s.rst
