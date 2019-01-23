:orphan:

.. sip:class:: PyQt5.QtWebSockets.QWebSocket
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWebSockets/QWebSocket-c.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.__init__
        :args:
            origin: str = ''
            version: :sip:ref:`~PyQt5.QtWebSockets.QWebSocketProtocol.Version` = :sip:ref:`~PyQt5.QtWebSockets.QWebSocketProtocol.Version.VersionLatest`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWebSockets/QWebSocket-__init__-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.abort
        :description: QtWebSockets/QWebSocket-abort-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.bytesToWrite
        :returns:
            int
        :description: QtWebSockets/QWebSocket-bytesToWrite-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.close
        :args:
            closeCode: :sip:ref:`~PyQt5.QtWebSockets.QWebSocketProtocol.CloseCode` = :sip:ref:`~PyQt5.QtWebSockets.QWebSocketProtocol.CloseCode.CloseCodeNormal`
            reason: str = ''
        :description: QtWebSockets/QWebSocket-close-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.closeCode
        :returns:
            :sip:ref:`~PyQt5.QtWebSockets.QWebSocketProtocol.CloseCode`
        :description: QtWebSockets/QWebSocket-closeCode-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.closeReason
        :returns:
            str
        :description: QtWebSockets/QWebSocket-closeReason-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.error
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketError`
        :description: QtWebSockets/QWebSocket-error-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.errorString
        :returns:
            str
        :description: QtWebSockets/QWebSocket-errorString-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.flush
        :returns:
            bool
        :description: QtWebSockets/QWebSocket-flush-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.ignoreSslErrors
        :description: QtWebSockets/QWebSocket-ignoreSslErrors-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.ignoreSslErrors
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QSslError`]
        :description: QtWebSockets/QWebSocket-ignoreSslErrors-f-1.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.isValid
        :returns:
            bool
        :description: QtWebSockets/QWebSocket-isValid-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.localAddress
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QHostAddress`
        :description: QtWebSockets/QWebSocket-localAddress-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.localPort
        :returns:
            int
        :description: QtWebSockets/QWebSocket-localPort-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.maskGenerator
        :returns:
            :sip:ref:`~PyQt5.QtWebSockets.QMaskGenerator`
        :description: QtWebSockets/QWebSocket-maskGenerator-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.open
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebSockets/QWebSocket-open-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.open
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
        :description: QtWebSockets/QWebSocket-open-f-1.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.origin
        :returns:
            str
        :description: QtWebSockets/QWebSocket-origin-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.pauseMode
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.PauseModes`
        :description: QtWebSockets/QWebSocket-pauseMode-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.peerAddress
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QHostAddress`
        :description: QtWebSockets/QWebSocket-peerAddress-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.peerName
        :returns:
            str
        :description: QtWebSockets/QWebSocket-peerName-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.peerPort
        :returns:
            int
        :description: QtWebSockets/QWebSocket-peerPort-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.ping
        :args:
            payload: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
        :description: QtWebSockets/QWebSocket-ping-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.proxy
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`
        :description: QtWebSockets/QWebSocket-proxy-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.readBufferSize
        :returns:
            int
        :description: QtWebSockets/QWebSocket-readBufferSize-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.request
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`
        :description: QtWebSockets/QWebSocket-request-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.requestUrl
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebSockets/QWebSocket-requestUrl-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.resourceName
        :returns:
            str
        :description: QtWebSockets/QWebSocket-resourceName-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.resume
        :description: QtWebSockets/QWebSocket-resume-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.sendBinaryMessage
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            int
        :description: QtWebSockets/QWebSocket-sendBinaryMessage-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.sendTextMessage
        :args:
            str
        :returns:
            int
        :description: QtWebSockets/QWebSocket-sendTextMessage-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.setMaskGenerator
        :args:
            :sip:ref:`~PyQt5.QtWebSockets.QMaskGenerator`
        :description: QtWebSockets/QWebSocket-setMaskGenerator-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.setPauseMode
        :args:
            Union[:sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.PauseModes`, :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.PauseMode`]
        :description: QtWebSockets/QWebSocket-setPauseMode-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.setProxy
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`
        :description: QtWebSockets/QWebSocket-setProxy-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.setReadBufferSize
        :args:
            int
        :description: QtWebSockets/QWebSocket-setReadBufferSize-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.setSslConfiguration
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :description: QtWebSockets/QWebSocket-setSslConfiguration-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.sslConfiguration
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration`
        :description: QtWebSockets/QWebSocket-sslConfiguration-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.state
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketState`
        :description: QtWebSockets/QWebSocket-state-f.rst

    .. sip:method:: PyQt5.QtWebSockets.QWebSocket.version
        :returns:
            :sip:ref:`~PyQt5.QtWebSockets.QWebSocketProtocol.Version`
        :description: QtWebSockets/QWebSocket-version-f.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.aboutToClose
        :description: QtWebSockets/QWebSocket-aboutToClose-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.binaryFrameReceived
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            bool
        :description: QtWebSockets/QWebSocket-binaryFrameReceived-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.binaryMessageReceived
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebSockets/QWebSocket-binaryMessageReceived-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.bytesWritten
        :args:
            int
        :description: QtWebSockets/QWebSocket-bytesWritten-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.connected
        :description: QtWebSockets/QWebSocket-connected-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.disconnected
        :description: QtWebSockets/QWebSocket-disconnected-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.error
        :description: QtWebSockets/QWebSocket-error-f-1.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.error
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketError`
        :description: QtWebSockets/QWebSocket-error-f.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.pong
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebSockets/QWebSocket-pong-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.preSharedKeyAuthenticationRequired
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QSslPreSharedKeyAuthenticator`
        :description: QtWebSockets/QWebSocket-preSharedKeyAuthenticationRequired-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.proxyAuthenticationRequired
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`
            :sip:ref:`~PyQt5.QtNetwork.QAuthenticator`
        :description: QtWebSockets/QWebSocket-proxyAuthenticationRequired-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.readChannelFinished
        :description: QtWebSockets/QWebSocket-readChannelFinished-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.sslErrors
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNetwork.QSslError`]
        :description: QtWebSockets/QWebSocket-sslErrors-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketState`
        :description: QtWebSockets/QWebSocket-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.textFrameReceived
        :args:
            str
            bool
        :description: QtWebSockets/QWebSocket-textFrameReceived-s.rst

    .. sip:signal:: PyQt5.QtWebSockets.QWebSocket.textMessageReceived
        :args:
            str
        :description: QtWebSockets/QWebSocket-textMessageReceived-s.rst
