.. sip:method-description::
    :status: todo
    :pysig: b02c08cbecae1811cfb64d3771553a51
    :realsig: (const QList<QSslCipher>&)
    :digest: 89393d5bb731d439eb372395b6a3bbb8

Sets the cryptographic cipher suite for this socket to *ciphers*, which must contain a subset of the ciphers in the list returned by supportedCiphers().

Restricting the cipher suite must be done before the handshake phase, where the session cipher is chosen.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.ciphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.
