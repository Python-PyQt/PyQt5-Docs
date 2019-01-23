.. sip:method-description::
    :status: todo
    :pysig: 6359afdf86b9ec14316ea3f79e266b65
    :realsig: () const
    :digest: ca1693c7c21a527a740594071d7ca1e9

Returns the data payload of this datagram. For a datagram received from the network, it contains the payload of the datagram. For an outgoing datagram, it is the datagram to be sent.

Note that datagrams can be transmitted with no data, so the returned :sip:ref:`~PyQt5.QtCore.QByteArray` may be empty.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram.setData`.
