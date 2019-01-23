:orphan:

.. sip:class:: PyQt5.QtNetwork.QNetworkConfigurationManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNetwork/QNetworkConfigurationManager-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability
        :description: QtNetwork/QNetworkConfigurationManager-Capability-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.ApplicationLevelRoaming
            :description: QtNetwork/QNetworkConfigurationManager-Capability-ApplicationLevelRoaming-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.CanStartAndStopInterfaces
            :description: QtNetwork/QNetworkConfigurationManager-Capability-CanStartAndStopInterfaces-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.DataStatistics
            :description: QtNetwork/QNetworkConfigurationManager-Capability-DataStatistics-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.DirectConnectionRouting
            :description: QtNetwork/QNetworkConfigurationManager-Capability-DirectConnectionRouting-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.ForcedRoaming
            :description: QtNetwork/QNetworkConfigurationManager-Capability-ForcedRoaming-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.NetworkSessionRequired
            :description: QtNetwork/QNetworkConfigurationManager-Capability-NetworkSessionRequired-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.SystemSessionSupport
            :description: QtNetwork/QNetworkConfigurationManager-Capability-SystemSessionSupport-v.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkConfigurationManager.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QNetworkConfigurationManager-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkConfigurationManager.allConfigurations
        :args:
            flags: Union[:sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlags`, :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.StateFlag`] = QNetworkConfiguration.StateFlags()
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`]
        :description: QtNetwork/QNetworkConfigurationManager-allConfigurations-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkConfigurationManager.capabilities
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.Capabilities`
        :description: QtNetwork/QNetworkConfigurationManager-capabilities-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkConfigurationManager.configurationFromIdentifier
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkConfigurationManager-configurationFromIdentifier-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkConfigurationManager.defaultConfiguration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkConfigurationManager-defaultConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkConfigurationManager.isOnline
        :returns:
            bool
        :description: QtNetwork/QNetworkConfigurationManager-isOnline-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkConfigurationManager.updateConfigurations
        :description: QtNetwork/QNetworkConfigurationManager-updateConfigurations-f.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkConfigurationManager.configurationAdded
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkConfigurationManager-configurationAdded-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkConfigurationManager.configurationChanged
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkConfigurationManager-configurationChanged-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkConfigurationManager.configurationRemoved
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkConfigurationManager-configurationRemoved-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkConfigurationManager.onlineStateChanged
        :args:
            bool
        :description: QtNetwork/QNetworkConfigurationManager-onlineStateChanged-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkConfigurationManager.updateCompleted
        :description: QtNetwork/QNetworkConfigurationManager-updateCompleted-s.rst
