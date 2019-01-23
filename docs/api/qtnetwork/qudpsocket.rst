:orphan:

.. sip:class:: PyQt5.QtNetwork.QUdpSocket
    :inherits: :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket`
    :description: QtNetwork/QUdpSocket-c.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QUdpSocket-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.hasPendingDatagrams
        :returns:
            bool
        :description: QtNetwork/QUdpSocket-hasPendingDatagrams-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.joinMulticastGroup
        :args:
            Union[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress`]
        :returns:
            bool
        :description: QtNetwork/QUdpSocket-joinMulticastGroup-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.joinMulticastGroup
        :args:
            Union[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress`]
            :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface`
        :returns:
            bool
        :description: QtNetwork/QUdpSocket-joinMulticastGroup-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.leaveMulticastGroup
        :args:
            Union[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress`]
        :returns:
            bool
        :description: QtNetwork/QUdpSocket-leaveMulticastGroup-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.leaveMulticastGroup
        :args:
            Union[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress`]
            :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface`
        :returns:
            bool
        :description: QtNetwork/QUdpSocket-leaveMulticastGroup-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.multicastInterface
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface`
        :description: QtNetwork/QUdpSocket-multicastInterface-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.pendingDatagramSize
        :returns:
            int
        :description: QtNetwork/QUdpSocket-pendingDatagramSize-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.readDatagram
        :args:
            int
        :returns:
            bytes
            :sip:ref:`~PyQt5.QtNetwork.QHostAddress`
            int
        :description: QtNetwork/QUdpSocket-readDatagram-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.receiveDatagram
        :args:
            maxSize: int = -1
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram`
        :description: QtNetwork/QUdpSocket-receiveDatagram-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.setMulticastInterface
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface`
        :description: QtNetwork/QUdpSocket-setMulticastInterface-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.writeDatagram
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram`
        :returns:
            int
        :description: QtNetwork/QUdpSocket-writeDatagram-f.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.writeDatagram
        :args:
            bytes
            Union[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress`]
            int
        :returns:
            int
        :description: QtNetwork/QUdpSocket-writeDatagram-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QUdpSocket.writeDatagram
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            Union[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress`]
            int
        :returns:
            int
        :description: QtNetwork/QUdpSocket-writeDatagram-f-2.rst
