.. sip:class-description::
    :status: todo
    :brief: Abstraction of one or more access point configurations
    :digest: c9558e90ed81e11d7de4e411abf44513

The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` class provides an abstraction of one or more access point configurations.

:sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` encapsulates a single access point or service network. In most cases a single access point configuration can be mapped to one network interface. However a single network interface may not always map to only one access point configuration. Multiple configurations for the same network device may enable multiple access points. An example device that could exhibit such a configuration might be a Smartphone which allows the user to manage multiple WLAN configurations while the device itself has only one WLAN network device.

The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` also supports the concept of service networks. This concept allows the grouping of multiple access point configurations into one entity. Such a group is called service network and can be beneficial in cases whereby a network session to a particular destination network is required (e.g. a company network). When using a service network the user doesn't usually care which one of the connectivity options is chosen (e.g. corporate WLAN or VPN via GPRS) as long as he can reach the company's target server. Depending on the current position and time some of the access points that make up the service network may not even be available. Furthermore automated access point roaming can be enabled which enables the device to change the network interface configuration dynamically while maintaining the applications connection to the target network. It allows adaption to the changing environment and may enable optimization with regards to cost, speed or other network parameters.

Special configurations of type :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.Type.UserChoice` provide a placeholder configuration which is resolved to an actual network configuration by the platform when a :sip:ref:`~PyQt5.QtNetwork.QNetworkSession` is :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.open`. Not all platforms support the concept of a user choice configuration.

.. _qnetworkconfiguration-configuration-states:

Configuration States
--------------------

The list of available configurations can be obtained via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.allConfigurations`. A configuration can have multiple states. The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Defined` configuration state indicates that the configuration is stored on the device. However the configuration is not yet ready to be activated as e.g. a WLAN may not be available at the current time.

The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Discovered` state implies that the configuration is :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Defined` and the outside conditions are such that the configuration can be used immediately to open a new network session. An example of such an outside condition may be that the Ethernet cable is actually connected to the device or that the WLAN with the specified SSID is in range.

The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Active` state implies that the configuration is :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Discovered`. A configuration in this state is currently being used by an application. The underlying network interface has a valid IP configuration and can transfer IP packets between the device and the target network.

The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Undefined` state indicates that the system has knowledge of possible target networks but cannot actually use that knowledge to connect to it. An example for such a state could be an encrypted WLAN that has been discovered but the user hasn't actually saved a configuration including the required password which would allow the device to connect to it.

Depending on the type of configuration some states are transient in nature. A GPRS/UMTS connection may almost always be :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Discovered` if the GSM/UMTS network is available. However if the GSM/UMTS network loses the connection the associated configuration may change its state from :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Discovered` to :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag.Defined` as well. A similar use case might be triggered by WLAN availability. :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateConfigurations` can be used to manually trigger updates of states. Note that some platforms do not require such updates as they implicitly change the state once it has been discovered. If the state of a configuration changes all related :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` instances change their state automatically.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession`, :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager`.
