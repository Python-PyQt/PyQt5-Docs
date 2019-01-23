.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (uint)
    :digest: bbdbd93b6c79518a1ab88b561a5712f2

Sets the interface index this datagram is associated with to *index*. The interface index is a positive number that uniquely identifies the network interface in the operating system. This number matches the value returned by :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface.index` for the interface.

It is usually not necessary to call this function on datagrams received from the network.

If this is an outgoing packet, this is the index of the interface the datagram should be sent on. A value of 0 indicates that the operating system should choose the interface based on other factors.

Note that the interface index can also be set with QHostAddress::setScopeId() for IPv6 destination addresses and then with :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.setDestination`. If the scope ID set in the destination address and *index* are different and neither is zero, it is undefined which interface the operating system will send the datagram on.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.interfaceIndex`.
