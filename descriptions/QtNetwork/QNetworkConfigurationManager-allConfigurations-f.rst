.. sip:method-description::
    :status: todo
    :pysig: 7f00890e9835571300e4067082c90192
    :realsig: (QNetworkConfiguration::StateFlags) const
    :digest: 22c5a58a27be4852537e4a81407ff110

Returns the list of configurations which comply with the given *filter*.

By default this function returns all (defined and undefined) configurations.

A wireless network with a particular SSID may only be accessible in a certain area despite the fact that the system has a valid configuration for it. Therefore the filter flag may be used to limit the list to discovered and possibly connected configurations only.

If *filter* is set to zero this function returns all possible configurations.

Note that this function returns the states for all configurations as they are known at the time of this function call. If for instance a configuration of type WLAN is defined the system may have to perform a WLAN scan in order to determine whether it is actually available. To obtain the most accurate state :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateConfigurations` should be used to update each configuration's state. Note that such an update may require some time. It's completion is signalled by :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateCompleted`. In the absence of a configuration update this function returns the best estimate at the time of the call. Therefore, if WLAN configurations are of interest, it is recommended that :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateConfigurations` is called once after :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager` instantiation (WLAN scans are too time consuming to perform in constructor). After this the data is kept automatically up-to-date as the system reports any changes.
