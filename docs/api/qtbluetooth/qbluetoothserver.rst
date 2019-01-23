:orphan:

.. sip:class:: PyQt5.QtBluetooth.QBluetoothServer
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtBluetooth/QBluetoothServer-c.rst

    .. sip:enum:: PyQt5.QtBluetooth.QBluetoothServer.Error
        :description: QtBluetooth/QBluetoothServer-Error-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothServer.Error.InputOutputError
            :description: QtBluetooth/QBluetoothServer-Error-InputOutputError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothServer.Error.NoError
            :description: QtBluetooth/QBluetoothServer-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothServer.Error.PoweredOffError
            :description: QtBluetooth/QBluetoothServer-Error-PoweredOffError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothServer.Error.ServiceAlreadyRegisteredError
            :description: QtBluetooth/QBluetoothServer-Error-ServiceAlreadyRegisteredError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothServer.Error.UnknownError
            :description: QtBluetooth/QBluetoothServer-Error-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothServer.Error.UnsupportedProtocolError
            :description: QtBluetooth/QBluetoothServer-Error-UnsupportedProtocolError-v.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.__init__
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo.Protocol`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QBluetoothServer-__init__-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.close
        :description: QtBluetooth/QBluetoothServer-close-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.error
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServer.Error`
        :description: QtBluetooth/QBluetoothServer-error-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.hasPendingConnections
        :returns:
            bool
        :description: QtBluetooth/QBluetoothServer-hasPendingConnections-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.isListening
        :returns:
            bool
        :description: QtBluetooth/QBluetoothServer-isListening-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.listen
        :args:
            address: :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress` = QBluetoothAddress()
            port: int = 0
        :returns:
            bool
        :description: QtBluetooth/QBluetoothServer-listen-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.listen
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`
            serviceName: str = ''
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo`
        :description: QtBluetooth/QBluetoothServer-listen-f-1.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.maxPendingConnections
        :returns:
            int
        :description: QtBluetooth/QBluetoothServer-maxPendingConnections-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.nextPendingConnection
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothSocket`
        :description: QtBluetooth/QBluetoothServer-nextPendingConnection-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.securityFlags
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetooth.SecurityFlags`
        :description: QtBluetooth/QBluetoothServer-securityFlags-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.serverAddress
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QBluetoothServer-serverAddress-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.serverPort
        :returns:
            int
        :description: QtBluetooth/QBluetoothServer-serverPort-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.serverType
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServiceInfo.Protocol`
        :description: QtBluetooth/QBluetoothServer-serverType-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.setMaxPendingConnections
        :args:
            int
        :description: QtBluetooth/QBluetoothServer-setMaxPendingConnections-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothServer.setSecurityFlags
        :args:
            Union[:sip:ref:`~PyQt5.QtBluetooth.QBluetooth.SecurityFlags`, :sip:ref:`~PyQt5.QtBluetooth.QBluetooth.Security`]
        :description: QtBluetooth/QBluetoothServer-setSecurityFlags-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothServer.error
        :description: QtBluetooth/QBluetoothServer-error-f-1.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothServer.error
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothServer.Error`
        :description: QtBluetooth/QBluetoothServer-error-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothServer.newConnection
        :description: QtBluetooth/QBluetoothServer-newConnection-s.rst
