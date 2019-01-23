.. sip:method-description::
    :status: todo
    :pysig: 6b4ec0c09210653836eac0355d7e1b26
    :realsig: () const
    :digest: acaf0ebcff219cf3a87509750e7740e9

Returns the sender address associated with this datagram. For a datagram received from the network, it is the address of the peer node that sent the datagram. For an outgoing datagrams, it is the local address to be used when sending.

If no sender address was set on this datagram, the returned object will report true to QHostAddress::isNull().

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.destinationAddress`, :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.senderPort`, :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.setSender`.
