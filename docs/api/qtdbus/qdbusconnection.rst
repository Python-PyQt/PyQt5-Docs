:orphan:

.. sip:class:: PyQt5.QtDBus.QDBusConnection
    :description: QtDBus/QDBusConnection-c.rst

    .. sip:enum:: PyQt5.QtDBus.QDBusConnection.BusType
        :description: QtDBus/QDBusConnection-BusType-e.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.BusType.ActivationBus
            :description: QtDBus/QDBusConnection-BusType-ActivationBus-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.BusType.SessionBus
            :description: QtDBus/QDBusConnection-BusType-SessionBus-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.BusType.SystemBus
            :description: QtDBus/QDBusConnection-BusType-SystemBus-v.rst

    .. sip:enum:: PyQt5.QtDBus.QDBusConnection.ConnectionCapability
        :description: QtDBus/QDBusConnection-ConnectionCapability-e.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.ConnectionCapability.UnixFileDescriptorPassing
            :description: QtDBus/QDBusConnection-ConnectionCapability-UnixFileDescriptorPassing-v.rst

    .. sip:enum:: PyQt5.QtDBus.QDBusConnection.RegisterOption
        :description: QtDBus/QDBusConnection-RegisterOption-e.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAdaptors
            :description: QtDBus/QDBusConnection-RegisterOption-ExportAdaptors-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAllContents
            :description: QtDBus/QDBusConnection-RegisterOption-ExportAllContents-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAllInvokables
            :description: QtDBus/QDBusConnection-RegisterOption-ExportAllInvokables-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAllProperties
            :description: QtDBus/QDBusConnection-RegisterOption-ExportAllProperties-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAllSignal
            :description: QtDBus/QDBusConnection-RegisterOption-ExportAllSignal-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAllSignals
            :description: QtDBus/QDBusConnection-RegisterOption-ExportAllSignals-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAllSlots
            :description: QtDBus/QDBusConnection-RegisterOption-ExportAllSlots-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportChildObjects
            :description: QtDBus/QDBusConnection-RegisterOption-ExportChildObjects-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportNonScriptableContents
            :description: QtDBus/QDBusConnection-RegisterOption-ExportNonScriptableContents-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportNonScriptableInvokables
            :description: QtDBus/QDBusConnection-RegisterOption-ExportNonScriptableInvokables-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportNonScriptableProperties
            :description: QtDBus/QDBusConnection-RegisterOption-ExportNonScriptableProperties-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportNonScriptableSignals
            :description: QtDBus/QDBusConnection-RegisterOption-ExportNonScriptableSignals-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportNonScriptableSlots
            :description: QtDBus/QDBusConnection-RegisterOption-ExportNonScriptableSlots-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportScriptableContents
            :description: QtDBus/QDBusConnection-RegisterOption-ExportScriptableContents-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportScriptableInvokables
            :description: QtDBus/QDBusConnection-RegisterOption-ExportScriptableInvokables-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportScriptableProperties
            :description: QtDBus/QDBusConnection-RegisterOption-ExportScriptableProperties-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportScriptableSignals
            :description: QtDBus/QDBusConnection-RegisterOption-ExportScriptableSignals-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportScriptableSlots
            :description: QtDBus/QDBusConnection-RegisterOption-ExportScriptableSlots-v.rst

    .. sip:enum:: PyQt5.QtDBus.QDBusConnection.UnregisterMode
        :description: QtDBus/QDBusConnection-UnregisterMode-e.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.UnregisterMode.UnregisterNode
            :description: QtDBus/QDBusConnection-UnregisterMode-UnregisterNode-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusConnection.UnregisterMode.UnregisterTree
            :description: QtDBus/QDBusConnection-UnregisterMode-UnregisterTree-v.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.__init__
        :args:
            str
        :description: QtDBus/QDBusConnection-__init__-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.__init__
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :description: QtDBus/QDBusConnection-__init__-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.asyncCall
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
            timeout: int = -1
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall`
        :description: QtDBus/QDBusConnection-asyncCall-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.baseService
        :returns:
            str
        :description: QtDBus/QDBusConnection-baseService-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.call
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
            mode: :sip:ref:`~PyQt5.QtDBus.QDBus.CallMode` = :sip:ref:`~PyQt5.QtDBus.QDBus.CallMode.Block`
            timeout: int = -1
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
        :description: QtDBus/QDBusConnection-call-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.callWithCallback
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
            PYQT_SLOT
            PYQT_SLOT
            timeout: int = -1
        :returns:
            bool
        :description: QtDBus/QDBusConnection-callWithCallback-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.connect
        :args:
            str
            str
            str
            str
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusConnection-connect-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.connect
        :args:
            str
            str
            str
            str
            str
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusConnection-connect-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.connect
        :args:
            str
            str
            str
            str
            Iterable[str]
            str
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusConnection-connect-f-2.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.connectionCapabilities
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection.ConnectionCapabilities`
        :description: QtDBus/QDBusConnection-connectionCapabilities-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.connectToBus
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection.BusType`
            str
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :static:
        :description: QtDBus/QDBusConnection-connectToBus-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.connectToBus
        :args:
            str
            str
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :static:
        :description: QtDBus/QDBusConnection-connectToBus-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.connectToPeer
        :args:
            str
            str
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :static:
        :description: QtDBus/QDBusConnection-connectToPeer-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.disconnect
        :args:
            str
            str
            str
            str
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusConnection-disconnect-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.disconnect
        :args:
            str
            str
            str
            str
            str
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusConnection-disconnect-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.disconnect
        :args:
            str
            str
            str
            str
            Iterable[str]
            str
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusConnection-disconnect-f-2.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.disconnectFromBus
        :args:
            str
        :static:
        :description: QtDBus/QDBusConnection-disconnectFromBus-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.disconnectFromPeer
        :args:
            str
        :static:
        :description: QtDBus/QDBusConnection-disconnectFromPeer-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.interface
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnectionInterface`
        :description: QtDBus/QDBusConnection-interface-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.isConnected
        :returns:
            bool
        :description: QtDBus/QDBusConnection-isConnected-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.lastError
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusError`
        :description: QtDBus/QDBusConnection-lastError-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.localMachineId
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :static:
        :description: QtDBus/QDBusConnection-localMachineId-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.name
        :returns:
            str
        :description: QtDBus/QDBusConnection-name-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.objectRegisteredAt
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtDBus/QDBusConnection-objectRegisteredAt-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.registerObject
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QObject`
            options: Union[:sip:ref:`~PyQt5.QtDBus.QDBusConnection.RegisterOptions`, :sip:ref:`~PyQt5.QtDBus.QDBusConnection.RegisterOption`] = :sip:ref:`~PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAdaptors`
        :returns:
            bool
        :description: QtDBus/QDBusConnection-registerObject-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.registerObject
        :args:
            str
            str
            :sip:ref:`~PyQt5.QtCore.QObject`
            options: Union[:sip:ref:`~PyQt5.QtDBus.QDBusConnection.RegisterOptions`, :sip:ref:`~PyQt5.QtDBus.QDBusConnection.RegisterOption`] = :sip:ref:`~PyQt5.QtDBus.QDBusConnection.RegisterOption.ExportAdaptors`
        :returns:
            bool
        :description: QtDBus/QDBusConnection-registerObject-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.registerService
        :args:
            str
        :returns:
            bool
        :description: QtDBus/QDBusConnection-registerService-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.send
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
        :returns:
            bool
        :description: QtDBus/QDBusConnection-send-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.sender
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :static:
        :description: QtDBus/QDBusConnection-sender-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.sessionBus
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :static:
        :description: QtDBus/QDBusConnection-sessionBus-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.swap
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :description: QtDBus/QDBusConnection-swap-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.systemBus
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :static:
        :description: QtDBus/QDBusConnection-systemBus-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.unregisterObject
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtDBus.QDBusConnection.UnregisterMode` = :sip:ref:`~PyQt5.QtDBus.QDBusConnection.UnregisterMode.UnregisterNode`
        :description: QtDBus/QDBusConnection-unregisterObject-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusConnection.unregisterService
        :args:
            str
        :returns:
            bool
        :description: QtDBus/QDBusConnection-unregisterService-f.rst
