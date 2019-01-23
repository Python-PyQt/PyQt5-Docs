.. sip:method-description::
    :status: todo
    :pysig: 91ed4c18559cd4da87c24935bcadf86d
    :realsig: (const QSslCertificate&)
    :digest: 77753989b9d868e83c0aa95259c2c2d6

Sets the certificate to be presented to the peer during SSL handshake to be *certificate*.

Setting the certificate once the connection has been established has no effect.

A certificate is the means of identification used in the SSL process. The local certificate is used by the remote end to verify the local user's identity against its list of Certification Authorities. In most cases, such as in HTTP web browsing, only servers identify to the clients, so the client does not send a certificate.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.localCertificate`.
