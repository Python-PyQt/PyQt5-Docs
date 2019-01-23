.. sip:method-description::
    :status: todo
    :pysig: bbc03c90e091505cf9ee4b711a272eac
    :realsig: () const
    :digest: d61458afb8b8c7ce6b50ee124975012d

Returns the socket's cryptographic :sip:ref:`~PyQt5.QtNetwork.QSslCipher`, or a null cipher if the connection isn't encrypted. The socket's cipher for the session is set during the handshake phase. The cipher is used to encrypt and decrypt data transmitted through the socket.

:sip:ref:`~PyQt5.QtNetwork.QSslSocket` also provides functions for setting the ordered list of ciphers from which the handshake phase will eventually select the session cipher. This ordered list must be in place before the handshake phase begins.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.ciphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.
