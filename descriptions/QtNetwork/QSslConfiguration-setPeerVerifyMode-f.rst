.. sip:method-description::
    :status: todo
    :pysig: 51be342ebf60717e7cb305d115307a67
    :realsig: (QSslSocket::PeerVerifyMode)
    :digest: 6f700319923f42df58bf22f55ba79c63

Sets the verify mode to *mode*. This mode decides whether :sip:ref:`~PyQt5.QtNetwork.QSslSocket` should request a certificate from the peer (i.e., the client requests a certificate from the server, or a server requesting a certificate from the client), and whether it should require that this certificate is valid.

The default mode is AutoVerifyPeer, which tells :sip:ref:`~PyQt5.QtNetwork.QSslSocket` to use VerifyPeer for clients, QueryPeer for servers.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.peerVerifyMode`.
