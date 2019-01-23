.. sip:method-description::
    :status: todo
    :pysig: 91ed4c18559cd4da87c24935bcadf86d
    :realsig: (const QSslCertificate&)
    :digest: 3234237fe0b5d71b0ce3e06f22557cd1

Adds the *certificate* to this socket's CA certificate database. The CA certificate database is used by the socket during the handshake phase to validate the peer's certificate.

To add multiple certificates, use :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificates`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.caCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCaCertificates`.
