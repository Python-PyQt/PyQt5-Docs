.. sip:method-description::
    :status: todo
    :pysig: 51be342ebf60717e7cb305d115307a67
    :realsig: (QSslSocket::PeerVerifyMode)
    :digest: fee79ae6cfb0626a6122cf544e2b6596

Sets the socket's verify mode to *mode*. This mode decides whether :sip:ref:`~PyQt5.QtNetwork.QSslSocket` should request a certificate from the peer (i.e., the client requests a certificate from the server, or a server requesting a certificate from the client), and whether it should require that this certificate is valid.

The default mode is :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode.AutoVerifyPeer`, which tells :sip:ref:`~PyQt5.QtNetwork.QSslSocket` to use :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode.VerifyPeer` for clients and :sip:ref:`~PyQt5.QtNetwork.QSslSocket.PeerVerifyMode.QueryPeer` for servers.

Setting this mode after encryption has started has no effect on the current connection.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.peerVerifyMode`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setPeerVerifyDepth`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.mode`.
