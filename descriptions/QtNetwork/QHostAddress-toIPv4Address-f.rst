.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: ca4a1e7be187188be072538dc8bc286c

Returns the IPv4 address as a number.

For example, if the address is 127.0.0.1, the returned value is 2130706433 (i.e. 0x7f000001).

This value is valid if the :sip:ref:`~PyQt5.QtNetwork.QHostAddress.protocol` is :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.NetworkLayerProtocol.IPv4Protocol`, or if the protocol is :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.NetworkLayerProtocol.IPv6Protocol`, and the IPv6 address is an IPv4 mapped address. (RFC4291)

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QHostAddress.toString`.
