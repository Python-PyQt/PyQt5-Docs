.. sip:method-description::
    :status: todo
    :pysig: 4d14d30c888d8c2abf70d5cbb24767f9
    :realsig: ()
    :digest: b0503d908a3bf6441e15eebf1079dc72

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.ciphers` on the default :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration` instead.

Returns the default cryptographic cipher suite for all sockets in this application. This list is used during the socket's handshake phase when negotiating with the peer to choose a session cipher. The list is ordered by preference (i.e., the first cipher in the list is the most preferred cipher).

By default, the handshake phase can choose any of the ciphers supported by this system's SSL libraries, which may vary from system to system. The list of ciphers supported by this system's SSL libraries is returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.
