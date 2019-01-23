:orphan:

.. sip:class:: PyQt5.QtNfc.QNearFieldTarget
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNfc/QNearFieldTarget-c.rst

    .. sip:enum:: PyQt5.QtNfc.QNearFieldTarget.AccessMethod
        :description: QtNfc/QNearFieldTarget-AccessMethod-e.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.AccessMethod.LlcpAccess
            :description: QtNfc/QNearFieldTarget-AccessMethod-LlcpAccess-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.AccessMethod.NdefAccess
            :description: QtNfc/QNearFieldTarget-AccessMethod-NdefAccess-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.AccessMethod.TagTypeSpecificAccess
            :description: QtNfc/QNearFieldTarget-AccessMethod-TagTypeSpecificAccess-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.AccessMethod.UnknownAccess
            :description: QtNfc/QNearFieldTarget-AccessMethod-UnknownAccess-v.rst

    .. sip:enum:: PyQt5.QtNfc.QNearFieldTarget.Error
        :description: QtNfc/QNearFieldTarget-Error-e.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.ChecksumMismatchError
            :description: QtNfc/QNearFieldTarget-Error-ChecksumMismatchError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.CommandError
            :description: QtNfc/QNearFieldTarget-Error-CommandError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.InvalidParametersError
            :description: QtNfc/QNearFieldTarget-Error-InvalidParametersError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.NdefReadError
            :description: QtNfc/QNearFieldTarget-Error-NdefReadError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.NdefWriteError
            :description: QtNfc/QNearFieldTarget-Error-NdefWriteError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.NoError
            :description: QtNfc/QNearFieldTarget-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.NoResponseError
            :description: QtNfc/QNearFieldTarget-Error-NoResponseError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.TargetOutOfRangeError
            :description: QtNfc/QNearFieldTarget-Error-TargetOutOfRangeError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.UnknownError
            :description: QtNfc/QNearFieldTarget-Error-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Error.UnsupportedError
            :description: QtNfc/QNearFieldTarget-Error-UnsupportedError-v.rst

    .. sip:enum:: PyQt5.QtNfc.QNearFieldTarget.Type
        :description: QtNfc/QNearFieldTarget-Type-e.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Type.MifareTag
            :description: QtNfc/QNearFieldTarget-Type-MifareTag-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Type.NfcTagType1
            :description: QtNfc/QNearFieldTarget-Type-NfcTagType1-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Type.NfcTagType2
            :description: QtNfc/QNearFieldTarget-Type-NfcTagType2-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Type.NfcTagType3
            :description: QtNfc/QNearFieldTarget-Type-NfcTagType3-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Type.NfcTagType4
            :description: QtNfc/QNearFieldTarget-Type-NfcTagType4-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldTarget.Type.ProprietaryTag
            :description: QtNfc/QNearFieldTarget-Type-ProprietaryTag-v.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNfc/QNearFieldTarget-__init__-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.accessMethods
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.AccessMethods`
        :description: QtNfc/QNearFieldTarget-accessMethods-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.disconnect
        :returns:
            bool
        :description: QtNfc/QNearFieldTarget-disconnect-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.handleResponse
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            bool
        :description: QtNfc/QNearFieldTarget-handleResponse-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.hasNdefMessage
        :returns:
            bool
        :description: QtNfc/QNearFieldTarget-hasNdefMessage-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.isProcessingCommand
        :returns:
            bool
        :description: QtNfc/QNearFieldTarget-isProcessingCommand-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.keepConnection
        :returns:
            bool
        :description: QtNfc/QNearFieldTarget-keepConnection-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.maxCommandLength
        :returns:
            int
        :description: QtNfc/QNearFieldTarget-maxCommandLength-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.readNdefMessages
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :description: QtNfc/QNearFieldTarget-readNdefMessages-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.reportError
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.Error`
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :description: QtNfc/QNearFieldTarget-reportError-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.requestResponse
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :returns:
            Any
        :description: QtNfc/QNearFieldTarget-requestResponse-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.sendCommand
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :description: QtNfc/QNearFieldTarget-sendCommand-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.sendCommands
        :args:
            Iterable[Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]]
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :description: QtNfc/QNearFieldTarget-sendCommands-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.setKeepConnection
        :args:
            bool
        :returns:
            bool
        :description: QtNfc/QNearFieldTarget-setKeepConnection-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.setResponseForRequest
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
            Any
            emitRequestCompleted: bool = True
        :description: QtNfc/QNearFieldTarget-setResponseForRequest-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.type
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.Type`
        :description: QtNfc/QNearFieldTarget-type-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.uid
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNfc/QNearFieldTarget-uid-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.url
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtNfc/QNearFieldTarget-url-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.waitForRequestCompleted
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
            msecs: int = 5000
        :returns:
            bool
        :description: QtNfc/QNearFieldTarget-waitForRequestCompleted-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldTarget.writeNdefMessages
        :args:
            Iterable[:sip:ref:`~PyQt5.QtNfc.QNdefMessage`]
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :description: QtNfc/QNearFieldTarget-writeNdefMessages-f.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldTarget.disconnected
        :description: QtNfc/QNearFieldTarget-disconnected-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldTarget.error
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.Error`
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :description: QtNfc/QNearFieldTarget-error-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldTarget.ndefMessageRead
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNdefMessage`
        :description: QtNfc/QNearFieldTarget-ndefMessageRead-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldTarget.ndefMessagesWritten
        :description: QtNfc/QNearFieldTarget-ndefMessagesWritten-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldTarget.requestCompleted
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget.RequestId`
        :description: QtNfc/QNearFieldTarget-requestCompleted-s.rst
