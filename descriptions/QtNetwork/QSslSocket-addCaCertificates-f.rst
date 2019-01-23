.. sip:method-description::
    :status: todo
    :pysig: 59168da4bc48efa69c4a3e728df28e92
    :realsig: (const QList<QSslCertificate>&)
    :digest: 0d9dbc4b9f38aedd068f564737ebd3bb

Adds the *certificates* to this socket's CA certificate database. The CA certificate database is used by the socket during the handshake phase to validate the peer's certificate.

For more precise control, use :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificate`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.caCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addDefaultCaCertificate`.
