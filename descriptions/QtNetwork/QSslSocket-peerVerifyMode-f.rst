.. sip:method-description::
    :status: todo
    :pysig: 51be342ebf60717e7cb305d115307a67
    :realsig: () const
    :digest: 85ba73c87779d86abd47b2838251e717

Returns the socket's verify mode. This mode decides whether :sip:ref:`~PyQt5.QtNetwork.QSslSocket` should request a certificate from the peer (i.e., the client requests a certificate from the server, or a server requesting a certificate from the client), and whether it should require that this certificate is valid.

The default mode is :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode.AutoVerifyPeer`, which tells :sip:ref:`~PyQt5.QtNetwork.QSslSocket` to use :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode.VerifyPeer` for clients and :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode.QueryPeer` for servers.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setPeerVerifyMode`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.peerVerifyDepth`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.mode`.
