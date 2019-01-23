.. sip:method-description::
    :status: todo
    :pysig: b02c08cbecae1811cfb64d3771553a51
    :realsig: (const QList<QSslCipher>&)
    :digest: 745f5a738a70e4acf5437eb4010f2ec4

USe :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setCiphers` instead.

Sets the cryptographic cipher suite for this socket to *ciphers*, which must contain a subset of the ciphers in the list returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.

Restricting the cipher suite must be done before the handshake phase, where the session cipher is chosen.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.ciphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.
