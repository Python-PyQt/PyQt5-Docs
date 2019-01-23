.. sip:method-description::
    :status: todo
    :pysig: 514fcfa55d08147ab125366d0125bf32
    :realsig: (const QHostAddress&)
    :digest: 2167b06a9e332de0fb91dc231e9ece8b

Joins the multicast group specified by *groupAddress* on the default interface chosen by the operating system. The socket must be in :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketState.BoundState`, otherwise an error occurs.

Note that if you are attempting to join an IPv4 group, your socket must not be bound using IPv6 (or in dual mode, using :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress.Any`). You must use QHostAddress::AnyIPv4 instead.

This function returns ``true`` if successful; otherwise it returns ``false`` and sets the socket error accordingly.

**Note:** Joining IPv6 multicast groups without an interface selection is not supported in all operating systems. Consider using the overload where the interface is specified.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.leaveMulticastGroup`.
