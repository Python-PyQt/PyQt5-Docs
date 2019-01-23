.. sip:method-description::
    :status: todo
    :pysig: 59168da4bc48efa69c4a3e728df28e92
    :realsig: (const QList<QSslCertificate>&)
    :digest: f1964563969fcde39399689fd6d64d30

Sets this socket's CA certificate database to be *certificates*. The certificate database must be set prior to the SSL handshake. The CA certificate database is used by the socket during the handshake phase to validate the peer's certificate.

**Note:** The default configuration uses the system CA certificate database. If that is not available (as is commonly the case on iOS), the default database is empty.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.caCertificates`.
