:orphan:

.. sip:class:: PyQt5.QtBluetooth.QBluetoothSocket
    :inherits: :sip:ref:`~PyQt5.QtCore.QIODevice`
    :description: QtBluetooth/QBluetoothSocket-c.rst

    .. sip:enum:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError
        :description: QtBluetooth/QBluetoothSocket-SocketError-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.HostNotFoundError
            :description: QtBluetooth/QBluetoothSocket-SocketError-HostNotFoundError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.NetworkError
            :description: QtBluetooth/QBluetoothSocket-SocketError-NetworkError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.NoSocketError
            :description: QtBluetooth/QBluetoothSocket-SocketError-NoSocketError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.OperationError
            :description: QtBluetooth/QBluetoothSocket-SocketError-OperationError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.RemoteHostClosedError
            :description: QtBluetooth/QBluetoothSocket-SocketError-RemoteHostClosedError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.ServiceNotFoundError
            :description: QtBluetooth/QBluetoothSocket-SocketError-ServiceNotFoundError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.UnknownSocketError
            :description: QtBluetooth/QBluetoothSocket-SocketError-UnknownSocketError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketError.UnsupportedProtocolError
            :description: QtBluetooth/QBluetoothSocket-SocketError-UnsupportedProtocolError-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState
        :description: QtBluetooth/QBluetoothSocket-SocketState-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState.BoundState
            :description: QtBluetooth/QBluetoothSocket-SocketState-BoundState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState.ClosingState
            :description: QtBluetooth/QBluetoothSocket-SocketState-ClosingState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState.ConnectedState
            :description: QtBluetooth/QBluetoothSocket-SocketState-ConnectedState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState.ConnectingState
            :description: QtBluetooth/QBluetoothSocket-SocketState-ConnectingState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState.ListeningState
            :description: QtBluetooth/QBluetoothSocket-SocketState-ListeningState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState.ServiceLookupState
            :description: QtBluetooth/QBluetoothSocket-SocketState-ServiceLookupState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothSocket.SocketState.UnconnectedState
            :description: QtBluetooth/QBluetoothSocket-SocketState-UnconnectedState-v.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QBluetoothSocket-__init__-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.__init__
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo.Protocol`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QBluetoothSocket-__init__-f-1.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.abort
        :description: QtBluetooth/QBluetoothSocket-abort-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.bytesAvailable
        :returns:
            int
        :description: QtBluetooth/QBluetoothSocket-bytesAvailable-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.bytesToWrite
        :returns:
            int
        :description: QtBluetooth/QBluetoothSocket-bytesToWrite-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.canReadLine
        :returns:
            bool
        :description: QtBluetooth/QBluetoothSocket-canReadLine-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.close
        :description: QtBluetooth/QBluetoothSocket-close-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.connectToService
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo`
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtBluetooth/QBluetoothSocket-connectToService-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.connectToService
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtBluetooth/QBluetoothSocket-connectToService-f-1.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.connectToService
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            int
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtBluetooth/QBluetoothSocket-connectToService-f-2.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.disconnectFromService
        :description: QtBluetooth/QBluetoothSocket-disconnectFromService-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.doDeviceDiscovery
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo`
            Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`]
        :description: QtBluetooth/QBluetoothSocket-doDeviceDiscovery-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.error
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketError`
        :description: QtBluetooth/QBluetoothSocket-error-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.errorString
        :returns:
            str
        :description: QtBluetooth/QBluetoothSocket-errorString-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.isSequential
        :returns:
            bool
        :description: QtBluetooth/QBluetoothSocket-isSequential-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.localAddress
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QBluetoothSocket-localAddress-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.localName
        :returns:
            str
        :description: QtBluetooth/QBluetoothSocket-localName-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.localPort
        :returns:
            int
        :description: QtBluetooth/QBluetoothSocket-localPort-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.peerAddress
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QBluetoothSocket-peerAddress-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.peerName
        :returns:
            str
        :description: QtBluetooth/QBluetoothSocket-peerName-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.peerPort
        :returns:
            int
        :description: QtBluetooth/QBluetoothSocket-peerPort-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.preferredSecurityFlags
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetooth.SecurityFlags`
        :description: QtBluetooth/QBluetoothSocket-preferredSecurityFlags-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.readData
        :args:
            int
        :returns:
            bytes
        :description: QtBluetooth/QBluetoothSocket-readData-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.setPreferredSecurityFlags
        :args:
            Union[:sip:ref:`~PyQt5.QtBluetooth.QBluetooth.SecurityFlags`, :sip:ref:`~PyQt5.QtBluetooth.QBluetooth.Security`]
        :description: QtBluetooth/QBluetoothSocket-setPreferredSecurityFlags-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.setSocketDescriptor
        :args:
            int
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo.Protocol`
            state: :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketState` = :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketState.ConnectedState`
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :returns:
            bool
        :description: QtBluetooth/QBluetoothSocket-setSocketDescriptor-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.setSocketError
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketError`
        :description: QtBluetooth/QBluetoothSocket-setSocketError-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.setSocketState
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketState`
        :description: QtBluetooth/QBluetoothSocket-setSocketState-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.socketDescriptor
        :returns:
            int
        :description: QtBluetooth/QBluetoothSocket-socketDescriptor-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.socketType
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo.Protocol`
        :description: QtBluetooth/QBluetoothSocket-socketType-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.state
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketState`
        :description: QtBluetooth/QBluetoothSocket-state-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothSocket.writeData
        :args:
            bytes
        :returns:
            int
        :description: QtBluetooth/QBluetoothSocket-writeData-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothSocket.connected
        :description: QtBluetooth/QBluetoothSocket-connected-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothSocket.disconnected
        :description: QtBluetooth/QBluetoothSocket-disconnected-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothSocket.error
        :description: QtBluetooth/QBluetoothSocket-error-f-1.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothSocket.error
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketError`
        :description: QtBluetooth/QBluetoothSocket-error-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothSocket.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket.SocketState`
        :description: QtBluetooth/QBluetoothSocket-stateChanged-s.rst
