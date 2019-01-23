.. sip:method-description::
    :status: todo
    :pysig: 59168da4bc48efa69c4a3e728df28e92
    :realsig: (const QList<QSslCertificate>&)
    :digest: 9cd208a0bd4c5f0d0099e7f1ee3ab686

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setCaCertificates` instead.

Sets this socket's CA certificate database to be *certificates*. The certificate database must be set prior to the SSL handshake. The CA certificate database is used by the socket during the handshake phase to validate the peer's certificate.

The CA certificate database can be reset to the current default CA certificate database by calling this function with the list of CA certificates returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCaCertificates`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.caCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCaCertificates`.
