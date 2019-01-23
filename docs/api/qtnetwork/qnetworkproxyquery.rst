:orphan:

.. sip:class:: PyQt5.QtNetwork.QNetworkProxyQuery
    :description: QtNetwork/QNetworkProxyQuery-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkProxyQuery.QueryType
        :description: QtNetwork/QNetworkProxyQuery-QueryType-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.SctpServer
            :description: QtNetwork/QNetworkProxyQuery-QueryType-SctpServer-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.SctpSocket
            :description: QtNetwork/QNetworkProxyQuery-QueryType-SctpSocket-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.TcpServer
            :description: QtNetwork/QNetworkProxyQuery-QueryType-TcpServer-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.TcpSocket
            :description: QtNetwork/QNetworkProxyQuery-QueryType-TcpSocket-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.UdpSocket
            :description: QtNetwork/QNetworkProxyQuery-QueryType-UdpSocket-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.UrlRequest
            :description: QtNetwork/QNetworkProxyQuery-QueryType-UrlRequest-v.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :description: QtNetwork/QNetworkProxyQuery-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery`
        :description: QtNetwork/QNetworkProxyQuery-__init__-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
            type: :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType` = :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.UrlRequest`
        :description: QtNetwork/QNetworkProxyQuery-__init__-f-2.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :args:
            int
            protocolTag: str = ''
            type: :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType` = :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.TcpServer`
        :description: QtNetwork/QNetworkProxyQuery-__init__-f-3.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
            :sip:ref:`~PyQt5.QtCore.QUrl`
            queryType: :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType` = :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.UrlRequest`
        :description: QtNetwork/QNetworkProxyQuery-__init__-f-4.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :args:
            str
            int
            protocolTag: str = ''
            type: :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType` = :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.TcpSocket`
        :description: QtNetwork/QNetworkProxyQuery-__init__-f-5.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
            int
            protocolTag: str = ''
            type: :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType` = :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.TcpServer`
        :description: QtNetwork/QNetworkProxyQuery-__init__-f-6.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
            str
            int
            protocolTag: str = ''
            type: :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType` = :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType.TcpSocket`
        :description: QtNetwork/QNetworkProxyQuery-__init__-f-7.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__eq__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery`
        :returns:
            bool
        :description: QtNetwork/QNetworkProxyQuery-__eq__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.localPort
        :returns:
            int
        :description: QtNetwork/QNetworkProxyQuery-localPort-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.__ne__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery`
        :returns:
            bool
        :description: QtNetwork/QNetworkProxyQuery-__ne__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.networkConfiguration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkProxyQuery-networkConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.peerHostName
        :returns:
            str
        :description: QtNetwork/QNetworkProxyQuery-peerHostName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.peerPort
        :returns:
            int
        :description: QtNetwork/QNetworkProxyQuery-peerPort-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.protocolTag
        :returns:
            str
        :description: QtNetwork/QNetworkProxyQuery-protocolTag-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.queryType
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType`
        :description: QtNetwork/QNetworkProxyQuery-queryType-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.setLocalPort
        :args:
            int
        :description: QtNetwork/QNetworkProxyQuery-setLocalPort-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.setNetworkConfiguration
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkProxyQuery-setNetworkConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.setPeerHostName
        :args:
            str
        :description: QtNetwork/QNetworkProxyQuery-setPeerHostName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.setPeerPort
        :args:
            int
        :description: QtNetwork/QNetworkProxyQuery-setPeerPort-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.setProtocolTag
        :args:
            str
        :description: QtNetwork/QNetworkProxyQuery-setProtocolTag-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.setQueryType
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery.QueryType`
        :description: QtNetwork/QNetworkProxyQuery-setQueryType-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.setUrl
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtNetwork/QNetworkProxyQuery-setUrl-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.swap
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyQuery`
        :description: QtNetwork/QNetworkProxyQuery-swap-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkProxyQuery.url
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtNetwork/QNetworkProxyQuery-url-f.rst
