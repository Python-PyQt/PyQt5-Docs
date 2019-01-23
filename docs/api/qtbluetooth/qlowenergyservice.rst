:orphan:

.. sip:class:: PyQt5.QtBluetooth.QLowEnergyService
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtBluetooth/QLowEnergyService-c.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError
        :description: QtBluetooth/QLowEnergyService-ServiceError-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError.CharacteristicReadError
            :description: QtBluetooth/QLowEnergyService-ServiceError-CharacteristicReadError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError.CharacteristicWriteError
            :description: QtBluetooth/QLowEnergyService-ServiceError-CharacteristicWriteError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError.DescriptorReadError
            :description: QtBluetooth/QLowEnergyService-ServiceError-DescriptorReadError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError.DescriptorWriteError
            :description: QtBluetooth/QLowEnergyService-ServiceError-DescriptorWriteError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError.NoError
            :description: QtBluetooth/QLowEnergyService-ServiceError-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError.OperationError
            :description: QtBluetooth/QLowEnergyService-ServiceError-OperationError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceError.UnknownError
            :description: QtBluetooth/QLowEnergyService-ServiceError-UnknownError-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyService.ServiceState
        :description: QtBluetooth/QLowEnergyService-ServiceState-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceState.DiscoveringServices
            :description: QtBluetooth/QLowEnergyService-ServiceState-DiscoveringServices-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceState.DiscoveryRequired
            :description: QtBluetooth/QLowEnergyService-ServiceState-DiscoveryRequired-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceState.InvalidService
            :description: QtBluetooth/QLowEnergyService-ServiceState-InvalidService-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceState.LocalService
            :description: QtBluetooth/QLowEnergyService-ServiceState-LocalService-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceState.ServiceDiscovered
            :description: QtBluetooth/QLowEnergyService-ServiceState-ServiceDiscovered-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyService.ServiceType
        :description: QtBluetooth/QLowEnergyService-ServiceType-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceType.IncludedService
            :description: QtBluetooth/QLowEnergyService-ServiceType-IncludedService-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.ServiceType.PrimaryService
            :description: QtBluetooth/QLowEnergyService-ServiceType-PrimaryService-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QLowEnergyService.WriteMode
        :description: QtBluetooth/QLowEnergyService-WriteMode-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.WriteMode.WriteSigned
            :description: QtBluetooth/QLowEnergyService-WriteMode-WriteSigned-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.WriteMode.WriteWithoutResponse
            :description: QtBluetooth/QLowEnergyService-WriteMode-WriteWithoutResponse-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QLowEnergyService.WriteMode.WriteWithResponse
            :description: QtBluetooth/QLowEnergyService-WriteMode-WriteWithResponse-v.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.characteristic
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`
        :description: QtBluetooth/QLowEnergyService-characteristic-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.characteristics
        :returns:
            List[:sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`]
        :description: QtBluetooth/QLowEnergyService-characteristics-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.contains
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`
        :returns:
            bool
        :description: QtBluetooth/QLowEnergyService-contains-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.contains
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyDescriptor`
        :returns:
            bool
        :description: QtBluetooth/QLowEnergyService-contains-f-1.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.discoverDetails
        :description: QtBluetooth/QLowEnergyService-discoverDetails-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.error
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService.ServiceError`
        :description: QtBluetooth/QLowEnergyService-error-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.includedServices
        :returns:
            List[:sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`]
        :description: QtBluetooth/QLowEnergyService-includedServices-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.readCharacteristic
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`
        :description: QtBluetooth/QLowEnergyService-readCharacteristic-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.readDescriptor
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyDescriptor`
        :description: QtBluetooth/QLowEnergyService-readDescriptor-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.serviceName
        :returns:
            str
        :description: QtBluetooth/QLowEnergyService-serviceName-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.serviceUuid
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothUuid`
        :description: QtBluetooth/QLowEnergyService-serviceUuid-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.state
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService.ServiceState`
        :description: QtBluetooth/QLowEnergyService-state-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.type
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService.ServiceTypes`
        :description: QtBluetooth/QLowEnergyService-type-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.writeCharacteristic
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            mode: :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService.WriteMode` = :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService.WriteMode.WriteWithResponse`
        :description: QtBluetooth/QLowEnergyService-writeCharacteristic-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QLowEnergyService.writeDescriptor
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyDescriptor`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtBluetooth/QLowEnergyService-writeDescriptor-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.characteristicChanged
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtBluetooth/QLowEnergyService-characteristicChanged-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.characteristicRead
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtBluetooth/QLowEnergyService-characteristicRead-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.characteristicWritten
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyCharacteristic`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtBluetooth/QLowEnergyService-characteristicWritten-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.descriptorRead
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyDescriptor`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtBluetooth/QLowEnergyService-descriptorRead-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.descriptorWritten
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyDescriptor`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtBluetooth/QLowEnergyService-descriptorWritten-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.error
        :description: QtBluetooth/QLowEnergyService-error-f-1.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.error
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService.ServiceError`
        :description: QtBluetooth/QLowEnergyService-error-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QLowEnergyService.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QLowEnergyService.ServiceState`
        :description: QtBluetooth/QLowEnergyService-stateChanged-s.rst
