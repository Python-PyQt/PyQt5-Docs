:orphan:

.. sip:class:: PyQt5.QtBluetooth.QBluetoothLocalDevice
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtBluetooth/QBluetoothLocalDevice-c.rst

    .. sip:enum:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Error
        :description: QtBluetooth/QBluetoothLocalDevice-Error-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Error.NoError
            :description: QtBluetooth/QBluetoothLocalDevice-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Error.PairingError
            :description: QtBluetooth/QBluetoothLocalDevice-Error-PairingError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Error.UnknownError
            :description: QtBluetooth/QBluetoothLocalDevice-Error-UnknownError-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode
        :description: QtBluetooth/QBluetoothLocalDevice-HostMode-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode.HostConnectable
            :description: QtBluetooth/QBluetoothLocalDevice-HostMode-HostConnectable-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode.HostDiscoverable
            :description: QtBluetooth/QBluetoothLocalDevice-HostMode-HostDiscoverable-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode.HostDiscoverableLimitedInquiry
            :description: QtBluetooth/QBluetoothLocalDevice-HostMode-HostDiscoverableLimitedInquiry-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode.HostPoweredOff
            :description: QtBluetooth/QBluetoothLocalDevice-HostMode-HostPoweredOff-v.rst

    .. sip:enum:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Pairing
        :description: QtBluetooth/QBluetoothLocalDevice-Pairing-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Pairing.AuthorizedPaired
            :description: QtBluetooth/QBluetoothLocalDevice-Pairing-AuthorizedPaired-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Pairing.Paired
            :description: QtBluetooth/QBluetoothLocalDevice-Pairing-Paired-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothLocalDevice.Pairing.Unpaired
            :description: QtBluetooth/QBluetoothLocalDevice-Pairing-Unpaired-v.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QBluetoothLocalDevice-__init__-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.__init__
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QBluetoothLocalDevice-__init__-f-1.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.address
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QBluetoothLocalDevice-address-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.allDevices
        :returns:
            List[:sip:ref:`~PyQt5.QtBluetooth.QBluetoothHostInfo`]
        :static:
        :description: QtBluetooth/QBluetoothLocalDevice-allDevices-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.connectedDevices
        :returns:
            List[:sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`]
        :description: QtBluetooth/QBluetoothLocalDevice-connectedDevices-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.hostMode
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode`
        :description: QtBluetooth/QBluetoothLocalDevice-hostMode-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.isValid
        :returns:
            bool
        :description: QtBluetooth/QBluetoothLocalDevice-isValid-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.name
        :returns:
            str
        :description: QtBluetooth/QBluetoothLocalDevice-name-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.pairingConfirmation
        :args:
            bool
        :description: QtBluetooth/QBluetoothLocalDevice-pairingConfirmation-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.pairingStatus
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothLocalDevice.Pairing`
        :description: QtBluetooth/QBluetoothLocalDevice-pairingStatus-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.powerOn
        :description: QtBluetooth/QBluetoothLocalDevice-powerOn-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.requestPairing
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothLocalDevice.Pairing`
        :description: QtBluetooth/QBluetoothLocalDevice-requestPairing-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothLocalDevice.setHostMode
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode`
        :description: QtBluetooth/QBluetoothLocalDevice-setHostMode-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothLocalDevice.deviceConnected
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QBluetoothLocalDevice-deviceConnected-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothLocalDevice.deviceDisconnected
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
        :description: QtBluetooth/QBluetoothLocalDevice-deviceDisconnected-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothLocalDevice.error
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothLocalDevice.Error`
        :description: QtBluetooth/QBluetoothLocalDevice-error-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothLocalDevice.hostModeStateChanged
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothLocalDevice.HostMode`
        :description: QtBluetooth/QBluetoothLocalDevice-hostModeStateChanged-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothLocalDevice.pairingDisplayConfirmation
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            str
        :description: QtBluetooth/QBluetoothLocalDevice-pairingDisplayConfirmation-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothLocalDevice.pairingDisplayPinCode
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            str
        :description: QtBluetooth/QBluetoothLocalDevice-pairingDisplayPinCode-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothLocalDevice.pairingFinished
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothAddress`
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothLocalDevice.Pairing`
        :description: QtBluetooth/QBluetoothLocalDevice-pairingFinished-s.rst
