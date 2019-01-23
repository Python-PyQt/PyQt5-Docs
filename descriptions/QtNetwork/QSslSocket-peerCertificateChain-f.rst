.. sip:method-description::
    :status: todo
    :pysig: abf4bf8f09df1317f3b5577332b00392
    :realsig: () const
    :digest: 0078f3d45c31dcf5ab530d682b16e951

Returns the peer's chain of digital certificates, or an empty list of certificates.

Peer certificates are checked automatically during the handshake phase. This function is normally used to fetch certificates for display, or for performing connection diagnostics. Certificates contain information about the peer and the certificate issuers, including host name, issuer names, and issuer public keys.

The peer certificates are set in :sip:ref:`~PyQt5.QtNetwork.QSslSocket` during the handshake phase, so it is safe to call this function from a slot connected to the :sip:ref:`~PyQt5.QtNetwork.QSslSocket.sslErrors` signal or the :sip:ref:`~PyQt5.QtNetwork.QSslSocket.encrypted` signal.

If an empty list is returned, it can mean the SSL handshake failed, or it can mean the host you are connected to doesn't have a certificate, or it can mean there is no connection.

If you want to get only the peer's immediate certificate, use :sip:ref:`~PyQt5.QtNetwork.QSslSocket.peerCertificate`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.peerCertificate`.
