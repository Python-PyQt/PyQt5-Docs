.. sip:method-description::
    :status: todo
    :pysig: 34f907787c5a37f6db3f4a9e4768a75c
    :realsig: (const QNetworkDatagram&)
    :digest: 364207e9a30a06f53d4855ef096f6772

This is an overloaded function.

Sends the datagram *datagram* to the host address and port numbers contained in *datagram*, using the network interface and hop count limits also set there. If the destination address and port numbers are unset, this function will send to the address that was passed to connectToHost().

If the destination address is IPv6 with a non-empty scope id but differs from the interface index in *datagram*, it is undefined which interface the operating system will choose to send on.

The function returns the number of bytes sent if it succeeded or -1 if it encountered an error.

**Warning:** Calling this function on a connected UDP socket may result in an error and no packet being sent. If you are using a connected socket, use write() to send datagrams.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.setDestination`, :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.setHopLimit`, :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.setInterfaceIndex`.
