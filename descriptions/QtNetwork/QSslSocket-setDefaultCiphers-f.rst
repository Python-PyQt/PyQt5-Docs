.. sip:method-description::
    :status: todo
    :pysig: 70a67dcc8e64467a776a4ac097a8de62
    :realsig: (const QList<QSslCipher>&)
    :digest: d44286447214ed4ded20e9b361fe095d

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setCiphers` on the default :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration` instead.

Sets the default cryptographic cipher suite for all sockets in this application to *ciphers*, which must contain a subset of the ciphers in the list returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.

Restricting the default cipher suite only affects SSL sockets that perform their handshake phase after the default cipher suite has been changed.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.
