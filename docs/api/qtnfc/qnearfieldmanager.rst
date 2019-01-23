:orphan:

.. sip:class:: PyQt5.QtNfc.QNearFieldManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNfc/QNearFieldManager-c.rst

    .. sip:enum:: PyQt5.QtNfc.QNearFieldManager.AdapterState
        :description: QtNfc/QNearFieldManager-AdapterState-e.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.AdapterState.Offline
            :description: QtNfc/QNearFieldManager-AdapterState-Offline-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.AdapterState.Online
            :description: QtNfc/QNearFieldManager-AdapterState-Online-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.AdapterState.TurningOff
            :description: QtNfc/QNearFieldManager-AdapterState-TurningOff-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.AdapterState.TurningOn
            :description: QtNfc/QNearFieldManager-AdapterState-TurningOn-v.rst

    .. sip:enum:: PyQt5.QtNfc.QNearFieldManager.TargetAccessMode
        :description: QtNfc/QNearFieldManager-TargetAccessMode-e.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.TargetAccessMode.NdefReadTargetAccess
            :description: QtNfc/QNearFieldManager-TargetAccessMode-NdefReadTargetAccess-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.TargetAccessMode.NdefWriteTargetAccess
            :description: QtNfc/QNearFieldManager-TargetAccessMode-NdefWriteTargetAccess-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.TargetAccessMode.NoTargetAccess
            :description: QtNfc/QNearFieldManager-TargetAccessMode-NoTargetAccess-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldManager.TargetAccessMode.TagTypeSpecificTargetAccess
            :description: QtNfc/QNearFieldManager-TargetAccessMode-TagTypeSpecificTargetAccess-v.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNfc/QNearFieldManager-__init__-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.isAvailable
        :returns:
            bool
        :description: QtNfc/QNearFieldManager-isAvailable-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.isSupported
        :returns:
            bool
        :description: QtNfc/QNearFieldManager-isSupported-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.registerNdefMessageHandler
        :args:
            PYQT_SLOT
        :returns:
            int
        :description: QtNfc/QNearFieldManager-registerNdefMessageHandler-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.registerNdefMessageHandler
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNdefFilter`
            PYQT_SLOT
        :returns:
            int
        :description: QtNfc/QNearFieldManager-registerNdefMessageHandler-f-1.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.registerNdefMessageHandler
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNdefRecord.TypeNameFormat`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            PYQT_SLOT
        :returns:
            int
        :description: QtNfc/QNearFieldManager-registerNdefMessageHandler-f-2.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.setTargetAccessModes
        :args:
            Union[:sip:ref:`~PyQt5.QtNfc.QNearFieldManager.TargetAccessModes`, :sip:ref:`~PyQt5.QtNfc.QNearFieldManager.TargetAccessMode`]
        :description: QtNfc/QNearFieldManager-setTargetAccessModes-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.startTargetDetection
        :returns:
            bool
        :description: QtNfc/QNearFieldManager-startTargetDetection-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.stopTargetDetection
        :description: QtNfc/QNearFieldManager-stopTargetDetection-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.targetAccessModes
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldManager.TargetAccessModes`
        :description: QtNfc/QNearFieldManager-targetAccessModes-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldManager.unregisterNdefMessageHandler
        :args:
            int
        :returns:
            bool
        :description: QtNfc/QNearFieldManager-unregisterNdefMessageHandler-f.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldManager.adapterStateChanged
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldManager.AdapterState`
        :description: QtNfc/QNearFieldManager-adapterStateChanged-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldManager.targetDetected
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget`
        :description: QtNfc/QNearFieldManager-targetDetected-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldManager.targetLost
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget`
        :description: QtNfc/QNearFieldManager-targetLost-s.rst
