.. sip:method-description::
    :status: todo
    :pysig: 6b4ec0c09210653836eac0355d7e1b26
    :realsig: () const
    :digest: 933d1c61436531cf912b281fd9eb86b2

Returns the destination address associated with this datagram. For a datagram received from the network, it is the address the peer node sent the datagram to, which can either be a local address of this machine or a multicast or broadcast address. For an outgoing datagrams, it is the address the datagram should be sent to.

If no destination address was set on this datagram, the returned object will report true to QHostAddress::isNull().

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.senderAddress`, :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.destinationPort`, :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.setDestination`.
