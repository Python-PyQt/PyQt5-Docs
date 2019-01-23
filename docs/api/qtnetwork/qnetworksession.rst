:orphan:

.. sip:class:: PyQt5.QtNetwork.QNetworkSession
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNetwork/QNetworkSession-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkSession.SessionError
        :description: QtNetwork/QNetworkSession-SessionError-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.SessionError.InvalidConfigurationError
            :description: QtNetwork/QNetworkSession-SessionError-InvalidConfigurationError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.SessionError.OperationNotSupportedError
            :description: QtNetwork/QNetworkSession-SessionError-OperationNotSupportedError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.SessionError.RoamingError
            :description: QtNetwork/QNetworkSession-SessionError-RoamingError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.SessionError.SessionAbortedError
            :description: QtNetwork/QNetworkSession-SessionError-SessionAbortedError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.SessionError.UnknownSessionError
            :description: QtNetwork/QNetworkSession-SessionError-UnknownSessionError-v.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkSession.State
        :description: QtNetwork/QNetworkSession-State-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.State.Closing
            :description: QtNetwork/QNetworkSession-State-Closing-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.State.Connected
            :description: QtNetwork/QNetworkSession-State-Connected-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.State.Connecting
            :description: QtNetwork/QNetworkSession-State-Connecting-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.State.Disconnected
            :description: QtNetwork/QNetworkSession-State-Disconnected-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.State.Invalid
            :description: QtNetwork/QNetworkSession-State-Invalid-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.State.NotAvailable
            :description: QtNetwork/QNetworkSession-State-NotAvailable-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.State.Roaming
            :description: QtNetwork/QNetworkSession-State-Roaming-v.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkSession.UsagePolicy
        :description: QtNetwork/QNetworkSession-UsagePolicy-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.UsagePolicy.NoBackgroundTrafficPolicy
            :description: QtNetwork/QNetworkSession-UsagePolicy-NoBackgroundTrafficPolicy-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkSession.UsagePolicy.NoPolicy
            :description: QtNetwork/QNetworkSession-UsagePolicy-NoPolicy-v.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QNetworkSession-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.accept
        :description: QtNetwork/QNetworkSession-accept-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.activeTime
        :returns:
            int
        :description: QtNetwork/QNetworkSession-activeTime-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.bytesReceived
        :returns:
            int
        :description: QtNetwork/QNetworkSession-bytesReceived-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.bytesWritten
        :returns:
            int
        :description: QtNetwork/QNetworkSession-bytesWritten-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.close
        :description: QtNetwork/QNetworkSession-close-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.configuration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkSession-configuration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.connectNotify
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaMethod`
        :description: QtNetwork/QNetworkSession-connectNotify-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.disconnectNotify
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaMethod`
        :description: QtNetwork/QNetworkSession-disconnectNotify-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.error
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.SessionError`
        :description: QtNetwork/QNetworkSession-error-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.errorString
        :returns:
            str
        :description: QtNetwork/QNetworkSession-errorString-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.ignore
        :description: QtNetwork/QNetworkSession-ignore-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.interface
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface`
        :description: QtNetwork/QNetworkSession-interface-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.isOpen
        :returns:
            bool
        :description: QtNetwork/QNetworkSession-isOpen-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.migrate
        :description: QtNetwork/QNetworkSession-migrate-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.open
        :description: QtNetwork/QNetworkSession-open-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.reject
        :description: QtNetwork/QNetworkSession-reject-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.sessionProperty
        :args:
            str
        :returns:
            Any
        :description: QtNetwork/QNetworkSession-sessionProperty-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.setSessionProperty
        :args:
            str
            Any
        :description: QtNetwork/QNetworkSession-setSessionProperty-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.state
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State`
        :description: QtNetwork/QNetworkSession-state-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.stop
        :description: QtNetwork/QNetworkSession-stop-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.usagePolicies
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.UsagePolicies`
        :description: QtNetwork/QNetworkSession-usagePolicies-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkSession.waitForOpened
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtNetwork/QNetworkSession-waitForOpened-f.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.closed
        :description: QtNetwork/QNetworkSession-closed-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.error
        :description: QtNetwork/QNetworkSession-error-f-1.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.error
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.SessionError`
        :description: QtNetwork/QNetworkSession-error-f.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.newConfigurationActivated
        :description: QtNetwork/QNetworkSession-newConfigurationActivated-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.opened
        :description: QtNetwork/QNetworkSession-opened-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.preferredConfigurationChanged
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
            bool
        :description: QtNetwork/QNetworkSession-preferredConfigurationChanged-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State`
        :description: QtNetwork/QNetworkSession-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkSession.usagePoliciesChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtNetwork.QNetworkSession.UsagePolicies`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.UsagePolicy`]
        :description: QtNetwork/QNetworkSession-usagePoliciesChanged-s.rst
