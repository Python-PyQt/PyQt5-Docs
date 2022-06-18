:orphan:

.. sip:class:: PyQt5.QtNetwork.QLocalServer
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNetwork/QLocalServer-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QLocalServer.SocketOption
        :description: QtNetwork/QLocalServer-SocketOption-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalServer.SocketOption.GroupAccessOption
            :description: QtNetwork/QLocalServer-SocketOption-GroupAccessOption-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalServer.SocketOption.OtherAccessOption
            :description: QtNetwork/QLocalServer-SocketOption-OtherAccessOption-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalServer.SocketOption.UserAccessOption
            :description: QtNetwork/QLocalServer-SocketOption-UserAccessOption-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QLocalServer.SocketOption.WorldAccessOption
            :description: QtNetwork/QLocalServer-SocketOption-WorldAccessOption-v.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QLocalServer-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.close
        :description: QtNetwork/QLocalServer-close-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.errorString
        :returns:
            str
        :description: QtNetwork/QLocalServer-errorString-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.fullServerName
        :returns:
            str
        :description: QtNetwork/QLocalServer-fullServerName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.hasPendingConnections
        :returns:
            bool
        :description: QtNetwork/QLocalServer-hasPendingConnections-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.incomingConnection
        :args:
            PyQt5.sip.voidptr
        :description: QtNetwork/QLocalServer-incomingConnection-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.isListening
        :returns:
            bool
        :description: QtNetwork/QLocalServer-isListening-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.listen
        :args:
            str
        :returns:
            bool
        :description: QtNetwork/QLocalServer-listen-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.listen
        :args:
            PyQt5.sip.voidptr
        :returns:
            bool
        :description: QtNetwork/QLocalServer-listen-f-2.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.maxPendingConnections
        :returns:
            int
        :description: QtNetwork/QLocalServer-maxPendingConnections-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.nextPendingConnection
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QLocalSocket`
        :description: QtNetwork/QLocalServer-nextPendingConnection-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.removeServer
        :args:
            str
        :returns:
            bool
        :static:
        :description: QtNetwork/QLocalServer-removeServer-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.serverError
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketError`
        :description: QtNetwork/QLocalServer-serverError-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.serverName
        :returns:
            str
        :description: QtNetwork/QLocalServer-serverName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.setMaxPendingConnections
        :args:
            int
        :description: QtNetwork/QLocalServer-setMaxPendingConnections-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.setSocketOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtNetwork.QLocalServer.SocketOptions`, :sip:ref:`~PyQt5.QtNetwork.QLocalServer.SocketOption`]
        :description: QtNetwork/QLocalServer-setSocketOptions-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.socketDescriptor
        :returns:
            PyQt5.sip.voidptr
        :description: QtNetwork/QLocalServer-socketDescriptor-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.socketOptions
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QLocalServer.SocketOptions`
        :description: QtNetwork/QLocalServer-socketOptions-f.rst

    .. sip:method:: PyQt5.QtNetwork.QLocalServer.waitForNewConnection
        :args:
            msecs: int = 0
        :returns:
            bool
            bool
        :description: QtNetwork/QLocalServer-waitForNewConnection-f.rst

    .. sip:signal:: PyQt5.QtNetwork.QLocalServer.newConnection
        :description: QtNetwork/QLocalServer-newConnection-s.rst
