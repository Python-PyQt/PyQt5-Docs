.. sip:method-description::
    :status: todo
    :pysig: 47f203c5796bcce251e8f8c90c148e94
    :realsig: (const QSslConfiguration&)
    :digest: 4482e854d10d5a7bbd4c20efa6ef8645

Sets the socket's SSL configuration to be the contents of *configuration*. This function sets the local certificate, the ciphers, the private key and the CA certificates to those stored in *configuration*.

It is not possible to set the SSL-state related fields.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.sslConfiguration`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setLocalCertificate`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setPrivateKey`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCaCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCiphers`.
