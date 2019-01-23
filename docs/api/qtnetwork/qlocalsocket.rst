:orphan:

.. sip:class:: PyQt5.QtNetwork.QLocalSocket
    :inherits: :sip:ref:`~PyQt5.QtCore.QIODevice`
    :description: QtNetwork/QLocalSocket-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError
        :description: QtNetwork/QLocalSocket-LocalSocketError-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.ConnectionError
            :description: QtNetwork/QLocalSocket-LocalSocketError-ConnectionError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.ConnectionRefusedError
            :description: QtNetwork/QLocalSocket-LocalSocketError-ConnectionRefusedError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.DatagramTooLargeError
            :description: QtNetwork/QLocalSocket-LocalSocketError-DatagramTooLargeError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.OperationError
            :description: QtNetwork/QLocalSocket-LocalSocketError-OperationError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.PeerClosedError
            :description: QtNetwork/QLocalSocket-LocalSocketError-PeerClosedError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.ServerNotFoundError
            :description: QtNetwork/QLocalSocket-LocalSocketError-ServerNotFoundError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.SocketAccessError
            :description: QtNetwork/QLocalSocket-LocalSocketError-SocketAccessError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.SocketResourceError
            :description: QtNetwork/QLocalSocket-LocalSocketError-SocketResourceError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.SocketTimeoutError
            :description: QtNetwork/QLocalSocket-LocalSocketError-SocketTimeoutError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.UnknownSocketError
            :description: QtNetwork/QLocalSocket-LocalSocketError-UnknownSocketError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketError.UnsupportedSocketOperationError
            :description: QtNetwork/QLocalSocket-LocalSocketError-UnsupportedSocketOperationError-v.rst

    .. sip:enum:: PyQt5.QtNetwork.QLocalSocket.LocalSocketState
        :description: QtNetwork/QLocalSocket-LocalSocketState-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketState.ClosingState
            :description: QtNetwork/QLocalSocket-LocalSocketState-ClosingState-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketState.ConnectedState
            :description: QtNetwork/QLocalSocket-LocalSocketState-ConnectedState-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketState.ConnectingState
            :description: QtNetwork/QLocalSocket-LocalSocketState-ConnectingState-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalSocket.LocalSocketState.UnconnectedState
            :description: QtNetwork/QLocalSocket-LocalSocketState-UnconnectedState-v.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QLocalSocket-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.abort
        :description: QtNetwork/QLocalSocket-abort-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.bytesAvailable
        :returns:
            int
        :description: QtNetwork/QLocalSocket-bytesAvailable-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.bytesToWrite
        :returns:
            int
        :description: QtNetwork/QLocalSocket-bytesToWrite-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.canReadLine
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-canReadLine-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.close
        :description: QtNetwork/QLocalSocket-close-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.connectToServer
        :args:
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtNetwork/QLocalSocket-connectToServer-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.connectToServer
        :args:
            str
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtNetwork/QLocalSocket-connectToServer-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.disconnectFromServer
        :description: QtNetwork/QLocalSocket-disconnectFromServer-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.error
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketError`
        :description: QtNetwork/QLocalSocket-error-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.flush
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-flush-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.fullServerName
        :returns:
            str
        :description: QtNetwork/QLocalSocket-fullServerName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.isSequential
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-isSequential-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.isValid
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-isValid-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.open
        :args:
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-open-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.readBufferSize
        :returns:
            int
        :description: QtNetwork/QLocalSocket-readBufferSize-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.readData
        :args:
            int
        :returns:
            bytes
        :description: QtNetwork/QLocalSocket-readData-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.serverName
        :returns:
            str
        :description: QtNetwork/QLocalSocket-serverName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.setReadBufferSize
        :args:
            int
        :description: QtNetwork/QLocalSocket-setReadBufferSize-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.setServerName
        :args:
            str
        :description: QtNetwork/QLocalSocket-setServerName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.setSocketDescriptor
        :args:
            sip.voidptr
            state: :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketState` = :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketState.ConnectedState`
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-setSocketDescriptor-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.socketDescriptor
        :returns:
            sip.voidptr
        :description: QtNetwork/QLocalSocket-socketDescriptor-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.state
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketState`
        :description: QtNetwork/QLocalSocket-state-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.waitForBytesWritten
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-waitForBytesWritten-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.waitForConnected
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-waitForConnected-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.waitForDisconnected
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-waitForDisconnected-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.waitForReadyRead
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtNetwork/QLocalSocket-waitForReadyRead-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalSocket.writeData
        :args:
            bytes
        :returns:
            int
        :description: QtNetwork/QLocalSocket-writeData-f.rst

    .. sip:signal:: PyQt5.QtNetwork.QLocalSocket.connected
        :description: QtNetwork/QLocalSocket-connected-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QLocalSocket.disconnected
        :description: QtNetwork/QLocalSocket-disconnected-s.rst

    .. sip:signal:: PyQt5.QtNetwork.QLocalSocket.error
        :description: QtNetwork/QLocalSocket-error-f-1.rst

    .. sip:signal:: PyQt5.QtNetwork.QLocalSocket.error
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketError`
        :description: QtNetwork/QLocalSocket-error-f.rst

    .. sip:signal:: PyQt5.QtNetwork.QLocalSocket.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketState`
        :description: QtNetwork/QLocalSocket-stateChanged-s.rst
