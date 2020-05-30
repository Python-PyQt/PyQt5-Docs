:orphan:

.. sip:class:: PyQt5.QtNetwork.QNetworkAccessManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNetwork/QNetworkAccessManager-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkAccessManager.NetworkAccessibility
        :description: QtNetwork/QNetworkAccessManager-NetworkAccessibility-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.NetworkAccessibility.Accessible
            :description: QtNetwork/QNetworkAccessManager-NetworkAccessibility-Accessible-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.NetworkAccessibility.NotAccessible
            :description: QtNetwork/QNetworkAccessManager-NetworkAccessibility-NotAccessible-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.NetworkAccessibility.UnknownAccessibility
            :description: QtNetwork/QNetworkAccessManager-NetworkAccessibility-UnknownAccessibility-v.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkAccessManager.Operation
        :description: QtNetwork/QNetworkAccessManager-Operation-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.Operation.CustomOperation
            :description: QtNetwork/QNetworkAccessManager-Operation-CustomOperation-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.Operation.DeleteOperation
            :description: QtNetwork/QNetworkAccessManager-Operation-DeleteOperation-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.Operation.GetOperation
            :description: QtNetwork/QNetworkAccessManager-Operation-GetOperation-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.Operation.HeadOperation
            :description: QtNetwork/QNetworkAccessManager-Operation-HeadOperation-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.Operation.PostOperation
            :description: QtNetwork/QNetworkAccessManager-Operation-PostOperation-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkAccessManager.Operation.PutOperation
            :description: QtNetwork/QNetworkAccessManager-Operation-PutOperation-v.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QNetworkAccessManager-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.activeConfiguration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkAccessManager-activeConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.addStrictTransportSecurityHosts
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QHstsPolicy`]
        :description: QtNetwork/QNetworkAccessManager-addStrictTransportSecurityHosts-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.autoDeleteReplies
        :returns:
            bool
        :description: QtNetwork/QNetworkAccessManager-autoDeleteReplies-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.cache
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractNetworkCache`
        :description: QtNetwork/QNetworkAccessManager-cache-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.clearAccessCache
        :description: QtNetwork/QNetworkAccessManager-clearAccessCache-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.clearConnectionCache
        :description: QtNetwork/QNetworkAccessManager-clearConnectionCache-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.configuration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkAccessManager-configuration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.connectToHost
        :args:
            str
            port: int = 80
        :description: QtNetwork/QNetworkAccessManager-connectToHost-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.connectToHostEncrypted
        :args:
            str
            port: int = 443
            sslConfiguration: :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration` = QSslConfiguration.defaultConfiguration()
        :description: QtNetwork/QNetworkAccessManager-connectToHostEncrypted-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.connectToHostEncrypted
        :args:
            str
            int
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
            str
        :description: QtNetwork/QNetworkAccessManager-connectToHostEncrypted-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.cookieJar
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar`
        :description: QtNetwork/QNetworkAccessManager-cookieJar-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.createRequest
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.Operation`
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            device: :sip:ref:`~PyQt5.QtCore.QIODevice` = None
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-createRequest-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.deleteResource
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-deleteResource-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.enableStrictTransportSecurityStore
        :args:
            bool
            storeDir: str = ''
        :description: QtNetwork/QNetworkAccessManager-enableStrictTransportSecurityStore-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.get
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-get-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.head
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-head-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.isStrictTransportSecurityEnabled
        :returns:
            bool
        :description: QtNetwork/QNetworkAccessManager-isStrictTransportSecurityEnabled-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.isStrictTransportSecurityStoreEnabled
        :returns:
            bool
        :description: QtNetwork/QNetworkAccessManager-isStrictTransportSecurityStoreEnabled-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.networkAccessible
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.NetworkAccessibility`
        :description: QtNetwork/QNetworkAccessManager-networkAccessible-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.post
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-post-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.post
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-post-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.post
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            :sip:ref:`~PyQt5.QtNetwork.QHttpMultiPart`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-post-f-2.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.proxy
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`
        :description: QtNetwork/QNetworkAccessManager-proxy-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.proxyFactory
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyFactory`
        :description: QtNetwork/QNetworkAccessManager-proxyFactory-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.put
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-put-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.put
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-put-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.put
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            :sip:ref:`~PyQt5.QtNetwork.QHttpMultiPart`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-put-f-2.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.redirectPolicy
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.RedirectPolicy`
        :description: QtNetwork/QNetworkAccessManager-redirectPolicy-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.sendCustomRequest
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            data: :sip:ref:`~PyQt5.QtCore.QIODevice` = None
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-sendCustomRequest-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.sendCustomRequest
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-sendCustomRequest-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.sendCustomRequest
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            :sip:ref:`~PyQt5.QtNetwork.QHttpMultiPart`
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-sendCustomRequest-f-2.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setAutoDeleteReplies
        :args:
            bool
        :description: QtNetwork/QNetworkAccessManager-setAutoDeleteReplies-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setCache
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractNetworkCache`
        :description: QtNetwork/QNetworkAccessManager-setCache-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setConfiguration
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`
        :description: QtNetwork/QNetworkAccessManager-setConfiguration-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setCookieJar
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar`
        :description: QtNetwork/QNetworkAccessManager-setCookieJar-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setNetworkAccessible
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.NetworkAccessibility`
        :description: QtNetwork/QNetworkAccessManager-setNetworkAccessible-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setProxy
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`
        :description: QtNetwork/QNetworkAccessManager-setProxy-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setProxyFactory
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxyFactory`
        :description: QtNetwork/QNetworkAccessManager-setProxyFactory-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setRedirectPolicy
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.RedirectPolicy`
        :description: QtNetwork/QNetworkAccessManager-setRedirectPolicy-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setStrictTransportSecurityEnabled
        :args:
            bool
        :description: QtNetwork/QNetworkAccessManager-setStrictTransportSecurityEnabled-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.setTransferTimeout
        :args:
            timeout: int = QNetworkRequest.TransferTimeoutConstant.DefaultTransferTimeoutConstant
        :description: QtNetwork/QNetworkAccessManager-setTransferTimeout-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.strictTransportSecurityHosts
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QHstsPolicy`]
        :description: QtNetwork/QNetworkAccessManager-strictTransportSecurityHosts-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.supportedSchemes
        :returns:
            List[str]
        :description: QtNetwork/QNetworkAccessManager-supportedSchemes-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.supportedSchemesImplementation
        :returns:
            List[str]
        :description: QtNetwork/QNetworkAccessManager-supportedSchemesImplementation-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkAccessManager.transferTimeout
        :returns:
            int
        :description: QtNetwork/QNetworkAccessManager-transferTimeout-f.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkAccessManager.authenticationRequired
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
            :sip:ref:`~PyQt5.QtNetwork.QAuthenticator`
        :description: QtNetwork/QNetworkAccessManager-authenticationRequired-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkAccessManager.encrypted
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-encrypted-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkAccessManager.finished
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetwork/QNetworkAccessManager-finished-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkAccessManager.networkAccessibleChanged
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.NetworkAccessibility`
        :description: QtNetwork/QNetworkAccessManager-networkAccessibleChanged-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkAccessManager.preSharedKeyAuthenticationRequired
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
            :sip:ref:`~PyQt5.QtNetwork.QSslPreSharedKeyAuthenticator`
        :description: QtNetwork/QNetworkAccessManager-preSharedKeyAuthenticationRequired-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkAccessManager.proxyAuthenticationRequired
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`
            :sip:ref:`~PyQt5.QtNetwork.QAuthenticator`
        :description: QtNetwork/QNetworkAccessManager-proxyAuthenticationRequired-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QNetworkAccessManager.sslErrors
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QSslError`]
        :description: QtNetwork/QNetworkAccessManager-sslErrors-s.rst
