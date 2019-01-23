:orphan:

.. sip:class:: PyQt5.QtBluetooth.QBluetoothTransferReply
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtBluetooth/QBluetoothTransferReply-c.rst

    .. sip:enum:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError
        :description: QtBluetooth/QBluetoothTransferReply-TransferError-e.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.FileNotFoundError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-FileNotFoundError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.HostNotFoundError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-HostNotFoundError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.IODeviceNotReadableError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-IODeviceNotReadableError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.NoError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.ResourceBusyError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-ResourceBusyError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.SessionError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-SessionError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.UnknownError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError.UserCanceledTransferError
            :description: QtBluetooth/QBluetoothTransferReply-TransferError-UserCanceledTransferError-v.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtBluetooth/QBluetoothTransferReply-__init__-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.abort
        :description: QtBluetooth/QBluetoothTransferReply-abort-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.error
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError`
        :description: QtBluetooth/QBluetoothTransferReply-error-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.errorString
        :returns:
            str
        :description: QtBluetooth/QBluetoothTransferReply-errorString-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.isFinished
        :returns:
            bool
        :description: QtBluetooth/QBluetoothTransferReply-isFinished-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.isRunning
        :returns:
            bool
        :description: QtBluetooth/QBluetoothTransferReply-isRunning-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.manager
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothTransferManager`
        :description: QtBluetooth/QBluetoothTransferReply-manager-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.request
        :returns:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothTransferRequest`
        :description: QtBluetooth/QBluetoothTransferReply-request-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.setManager
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothTransferManager`
        :description: QtBluetooth/QBluetoothTransferReply-setManager-f.rst

    .. sip:method:: PyQt5.QtBluetooth.QBluetoothTransferReply.setRequest
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothTransferRequest`
        :description: QtBluetooth/QBluetoothTransferReply-setRequest-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothTransferReply.error
        :description: QtBluetooth/QBluetoothTransferReply-error-f-1.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothTransferReply.error
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothTransferReply.TransferError`
        :description: QtBluetooth/QBluetoothTransferReply-error-f.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothTransferReply.finished
        :args:
            :sip:ref:`~PyQt5.QtBluetooth.QBluetoothTransferReply`
        :description: QtBluetooth/QBluetoothTransferReply-finished-s.rst

    .. sip:signal:: PyQt5.QtBluetooth.QBluetoothTransferReply.transferProgress
        :args:
            int
            int
        :description: QtBluetooth/QBluetoothTransferReply-transferProgress-s.rst
