.. sip:method-description::
    :status: todo
    :pysig: 47f203c5796bcce251e8f8c90c148e94
    :realsig: () const
    :digest: d1082a9497d989621c44672a016420ae

Returns the socket's SSL configuration state. The default SSL configuration of a socket is to use the default ciphers, default CA certificates, no local private key or certificate.

The SSL configuration also contains fields that can change with time without notice.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setSslConfiguration`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.localCertificate`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.peerCertificate`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.peerCertificateChain`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.sessionCipher`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.privateKey`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.ciphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.caCertificates`.
