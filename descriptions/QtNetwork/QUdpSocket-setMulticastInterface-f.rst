.. sip:method-description::
    :status: todo
    :pysig: f26d8363b0fa5bd8f8bda48d3005be38
    :realsig: (const QNetworkInterface&)
    :digest: 7346bbf40220bd356b1e7ff10c65cfb7

Sets the outgoing interface for multicast datagrams to the interface *iface*. This corresponds to the IP_MULTICAST_IF socket option for IPv4 sockets and the IPV6_MULTICAST_IF socket option for IPv6 sockets. The socket must be in :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketState.BoundState`, otherwise this function does nothing.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.multicastInterface`, :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.joinMulticastGroup`, :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.leaveMulticastGroup`.
