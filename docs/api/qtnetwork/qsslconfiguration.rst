:orphan:

.. sip:class:: PyQt5.QtNetwork.QSslConfiguration
    :description: QtNetwork/QSslConfiguration-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QSslConfiguration.NextProtocolNegotiationStatus
        :description: QtNetwork/QSslConfiguration-NextProtocolNegotiationStatus-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QSslConfiguration.NextProtocolNegotiationStatus.NextProtocolNegotiationNegotiated
            :description: QtNetwork/QSslConfiguration-NextProtocolNegotiationStatus-NextProtocolNegotiationNegotiated-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QSslConfiguration.NextProtocolNegotiationStatus.NextProtocolNegotiationNone
            :description: QtNetwork/QSslConfiguration-NextProtocolNegotiationStatus-NextProtocolNegotiationNone-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QSslConfiguration.NextProtocolNegotiationStatus.NextProtocolNegotiationUnsupported
            :description: QtNetwork/QSslConfiguration-NextProtocolNegotiationStatus-NextProtocolNegotiationUnsupported-v.rst

    .. sip:attribute:: PyQt5.QtNetwork.QSslConfiguration.NextProtocolHttp1_1
        :type: str
        :const:
        :static:
        :description: QtNetwork/QSslConfiguration-NextProtocolHttp1_1-a.rst

    .. sip:attribute:: PyQt5.QtNetwork.QSslConfiguration.NextProtocolSpdy3_0
        :type: str
        :const:
        :static:
        :description: QtNetwork/QSslConfiguration-NextProtocolSpdy3_0-a.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.__init__
        :description: QtNetwork/QSslConfiguration-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :description: QtNetwork/QSslConfiguration-__init__-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.allowedNextProtocols
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtNetwork/QSslConfiguration-allowedNextProtocols-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.backendConfiguration
        :returns:
            Dict[:sip:ref:`~PyQt5.QtCore.QByteArray`, Any]
        :description: QtNetwork/QSslConfiguration-backendConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.caCertificates
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslCertificate`]
        :description: QtNetwork/QSslConfiguration-caCertificates-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.ciphers
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslCipher`]
        :description: QtNetwork/QSslConfiguration-ciphers-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.defaultConfiguration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :static:
        :description: QtNetwork/QSslConfiguration-defaultConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.diffieHellmanParameters
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslDiffieHellmanParameters`
        :description: QtNetwork/QSslConfiguration-diffieHellmanParameters-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.ellipticCurves
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslEllipticCurve`]
        :description: QtNetwork/QSslConfiguration-ellipticCurves-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.ephemeralServerKey
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslKey`
        :description: QtNetwork/QSslConfiguration-ephemeralServerKey-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.__eq__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :returns:
            bool
        :description: QtNetwork/QSslConfiguration-__eq__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.isNull
        :returns:
            bool
        :description: QtNetwork/QSslConfiguration-isNull-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.localCertificate
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslCertificate`
        :description: QtNetwork/QSslConfiguration-localCertificate-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.localCertificateChain
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslCertificate`]
        :description: QtNetwork/QSslConfiguration-localCertificateChain-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.__ne__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :returns:
            bool
        :description: QtNetwork/QSslConfiguration-__ne__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.nextNegotiatedProtocol
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNetwork/QSslConfiguration-nextNegotiatedProtocol-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.nextProtocolNegotiationStatus
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.NextProtocolNegotiationStatus`
        :description: QtNetwork/QSslConfiguration-nextProtocolNegotiationStatus-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.ocspStaplingEnabled
        :returns:
            bool
        :description: QtNetwork/QSslConfiguration-ocspStaplingEnabled-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.peerCertificate
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslCertificate`
        :description: QtNetwork/QSslConfiguration-peerCertificate-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.peerCertificateChain
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslCertificate`]
        :description: QtNetwork/QSslConfiguration-peerCertificateChain-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.peerVerifyDepth
        :returns:
            int
        :description: QtNetwork/QSslConfiguration-peerVerifyDepth-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.peerVerifyMode
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode`
        :description: QtNetwork/QSslConfiguration-peerVerifyMode-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.preSharedKeyIdentityHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNetwork/QSslConfiguration-preSharedKeyIdentityHint-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.privateKey
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslKey`
        :description: QtNetwork/QSslConfiguration-privateKey-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.protocol
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSsl.SslProtocol`
        :description: QtNetwork/QSslConfiguration-protocol-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.sessionCipher
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslCipher`
        :description: QtNetwork/QSslConfiguration-sessionCipher-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.sessionProtocol
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSsl.SslProtocol`
        :description: QtNetwork/QSslConfiguration-sessionProtocol-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.sessionTicket
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNetwork/QSslConfiguration-sessionTicket-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.sessionTicketLifeTimeHint
        :returns:
            int
        :description: QtNetwork/QSslConfiguration-sessionTicketLifeTimeHint-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setAllowedNextProtocols
        :args:
            Iterable[Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]]
        :description: QtNetwork/QSslConfiguration-setAllowedNextProtocols-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setBackendConfiguration
        :args:
            backendConfiguration: Dict[Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray], Any] = {}
        :description: QtNetwork/QSslConfiguration-setBackendConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setBackendConfigurationOption
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            Any
        :description: QtNetwork/QSslConfiguration-setBackendConfigurationOption-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setCaCertificates
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QSslCertificate`]
        :description: QtNetwork/QSslConfiguration-setCaCertificates-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setCiphers
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QSslCipher`]
        :description: QtNetwork/QSslConfiguration-setCiphers-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setDefaultConfiguration
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :static:
        :description: QtNetwork/QSslConfiguration-setDefaultConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setDiffieHellmanParameters
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslDiffieHellmanParameters`
        :description: QtNetwork/QSslConfiguration-setDiffieHellmanParameters-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setEllipticCurves
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QSslEllipticCurve`]
        :description: QtNetwork/QSslConfiguration-setEllipticCurves-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setLocalCertificate
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslCertificate`
        :description: QtNetwork/QSslConfiguration-setLocalCertificate-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setLocalCertificateChain
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QSslCertificate`]
        :description: QtNetwork/QSslConfiguration-setLocalCertificateChain-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setOcspStaplingEnabled
        :args:
            bool
        :description: QtNetwork/QSslConfiguration-setOcspStaplingEnabled-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setPeerVerifyDepth
        :args:
            int
        :description: QtNetwork/QSslConfiguration-setPeerVerifyDepth-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setPeerVerifyMode
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode`
        :description: QtNetwork/QSslConfiguration-setPeerVerifyMode-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setPreSharedKeyIdentityHint
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtNetwork/QSslConfiguration-setPreSharedKeyIdentityHint-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setPrivateKey
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslKey`
        :description: QtNetwork/QSslConfiguration-setPrivateKey-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setProtocol
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSsl.SslProtocol`
        :description: QtNetwork/QSslConfiguration-setProtocol-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setSessionTicket
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtNetwork/QSslConfiguration-setSessionTicket-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.setSslOption
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSsl.SslOption`
            bool
        :description: QtNetwork/QSslConfiguration-setSslOption-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.supportedCiphers
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslCipher`]
        :static:
        :description: QtNetwork/QSslConfiguration-supportedCiphers-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.supportedEllipticCurves
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslEllipticCurve`]
        :static:
        :description: QtNetwork/QSslConfiguration-supportedEllipticCurves-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.swap
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :description: QtNetwork/QSslConfiguration-swap-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.systemCaCertificates
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QSslCertificate`]
        :static:
        :description: QtNetwork/QSslConfiguration-systemCaCertificates-f.rst

    .. sip:method:: PyQt5.QtNetwork.QSslConfiguration.testSslOption
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSsl.SslOption`
        :returns:
            bool
        :description: QtNetwork/QSslConfiguration-testSslOption-f.rst
