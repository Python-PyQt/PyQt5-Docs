.. sip:class-description::
    :status: todo
    :brief: Manages the network configurations provided by the system
    :digest: cca390fd66534c11a7874e4f94bc15f3

The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager` class manages the network configurations provided by the system.

:sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager` provides access to the network configurations known to the system and enables applications to detect the system capabilities (with regards to network sessions) at runtime.

A :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` abstracts a set of configuration options describing how a network interface has to be configured to connect to a particular target network. :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager` maintains and updates the global list of QNetworkConfigurations. Applications can access and filter this list via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.allConfigurations`. If a new configuration is added or an existing one is removed or changed the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.configurationAdded`, :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.configurationRemoved` and :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.configurationChanged` signals are emitted respectively.

The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.defaultConfiguration` can be used when intending to immediately create a new network session without caring about the particular configuration. It returns a :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Discovered` configuration. If there are not any discovered ones an invalid configuration is returned.

Some configuration updates may require some time to perform updates. A WLAN scan is such an example. Unless the platform performs internal updates it may be required to manually trigger configuration updates via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateConfigurations`. The completion of the update process is indicated by emitting the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateCompleted` signal. The update process ensures that every existing :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` instance is updated. There is no need to ask for a renewed configuration list via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.allConfigurations`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`.
