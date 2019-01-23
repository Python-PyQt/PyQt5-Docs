:orphan:

.. sip:class:: PyQt5.QtBluetooth.QLowEnergyController
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtBluetooth/QLowEnergyController-c.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState
        :description: QtBluetooth/QLowEnergyController-ControllerState-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState.AdvertisingState
            :description: QtBluetooth/QLowEnergyController-ControllerState-AdvertisingState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState.ClosingState
            :description: QtBluetooth/QLowEnergyController-ControllerState-ClosingState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState.ConnectedState
            :description: QtBluetooth/QLowEnergyController-ControllerState-ConnectedState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState.ConnectingState
            :description: QtBluetooth/QLowEnergyController-ControllerState-ConnectingState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState.DiscoveredState
            :description: QtBluetooth/QLowEnergyController-ControllerState-DiscoveredState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState.DiscoveringState
            :description: QtBluetooth/QLowEnergyController-ControllerState-DiscoveringState-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.ControllerState.UnconnectedState
            :description: QtBluetooth/QLowEnergyController-ControllerState-UnconnectedState-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyController.Error
        :description: QtBluetooth/QLowEnergyController-Error-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.AdvertisingError
            :description: QtBluetooth/QLowEnergyController-Error-AdvertisingError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.ConnectionError
            :description: QtBluetooth/QLowEnergyController-Error-ConnectionError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.InvalidBluetoothAdapterError
            :description: QtBluetooth/QLowEnergyController-Error-InvalidBluetoothAdapterError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.NetworkError
            :description: QtBluetooth/QLowEnergyController-Error-NetworkError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.NoError
            :description: QtBluetooth/QLowEnergyController-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.RemoteHostClosedError
            :description: QtBluetooth/QLowEnergyController-Error-RemoteHostClosedError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.UnknownError
            :description: QtBluetooth/QLowEnergyController-Error-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Error.UnknownRemoteDeviceError
            :description: QtBluetooth/QLowEnergyController-Error-UnknownRemoteDeviceError-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyController.RemoteAddressType
        :description: QtBluetooth/QLowEnergyController-RemoteAddressType-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.RemoteAddressType.PublicAddress
            :description: QtBluetooth/QLowEnergyController-RemoteAddressType-PublicAddress-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.RemoteAddressType.RandomAddress
            :description: QtBluetooth/QLowEnergyController-RemoteAddressType-RandomAddress-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyController.Role
        :description: QtBluetooth/QLowEnergyController-Role-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Role.CentralRole
            :description: QtBluetooth/QLowEnergyController-Role-CentralRole-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyController.Role.PeripheralRole
            :description: QtBluetooth/QLowEnergyController-Role-PeripheralRole-v.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.__init__
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothDeviceInfo`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QLowEnergyController-__init__-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.__init__
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QLowEnergyController-__init__-f-1.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.__init__
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QLowEnergyController-__init__-f-2.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.addService
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyServiceData`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService`
        :description: QtBluetooth/QLowEnergyController-addService-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.connectToDevice
        :description: QtBluetooth/QLowEnergyController-connectToDevice-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.createCentral
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothDeviceInfo`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController`
        :static:
        :description: QtBluetooth/QLowEnergyController-createCentral-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.createPeripheral
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController`
        :static:
        :description: QtBluetooth/QLowEnergyController-createPeripheral-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.createServiceObject
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService`
        :description: QtBluetooth/QLowEnergyController-createServiceObject-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.disconnectFromDevice
        :description: QtBluetooth/QLowEnergyController-disconnectFromDevice-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.discoverServices
        :description: QtBluetooth/QLowEnergyController-discoverServices-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.error
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController.Error`
        :description: QtBluetooth/QLowEnergyController-error-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.errorString
        :returns:
            str
        :description: QtBluetooth/QLowEnergyController-errorString-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.localAddress
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QLowEnergyController-localAddress-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.remoteAddress
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QLowEnergyController-remoteAddress-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.remoteAddressType
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController.RemoteAddressType`
        :description: QtBluetooth/QLowEnergyController-remoteAddressType-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.remoteDeviceUuid
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`
        :description: QtBluetooth/QLowEnergyController-remoteDeviceUuid-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.remoteName
        :returns:
            str
        :description: QtBluetooth/QLowEnergyController-remoteName-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.requestConnectionUpdate
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyConnectionParameters`
        :description: QtBluetooth/QLowEnergyController-requestConnectionUpdate-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.role
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController.Role`
        :description: QtBluetooth/QLowEnergyController-role-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.services
        :returns:
            List[:sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`]
        :description: QtBluetooth/QLowEnergyController-services-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.setRemoteAddressType
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController.RemoteAddressType`
        :description: QtBluetooth/QLowEnergyController-setRemoteAddressType-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.startAdvertising
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyAdvertisingParameters`
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyAdvertisingData`
            scanResponseData: :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyAdvertisingData` = QLowEnergyAdvertisingData()
        :description: QtBluetooth/QLowEnergyController-startAdvertising-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.state
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController.ControllerState`
        :description: QtBluetooth/QLowEnergyController-state-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyController.stopAdvertising
        :description: QtBluetooth/QLowEnergyController-stopAdvertising-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.connected
        :description: QtBluetooth/QLowEnergyController-connected-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.connectionUpdated
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyConnectionParameters`
        :description: QtBluetooth/QLowEnergyController-connectionUpdated-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.disconnected
        :description: QtBluetooth/QLowEnergyController-disconnected-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.discoveryFinished
        :description: QtBluetooth/QLowEnergyController-discoveryFinished-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.error
        :description: QtBluetooth/QLowEnergyController-error-f-1.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.error
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController.Error`
        :description: QtBluetooth/QLowEnergyController-error-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.serviceDiscovered
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`
        :description: QtBluetooth/QLowEnergyController-serviceDiscovered-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyController.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyController.ControllerState`
        :description: QtBluetooth/QLowEnergyController-stateChanged-s.rst
