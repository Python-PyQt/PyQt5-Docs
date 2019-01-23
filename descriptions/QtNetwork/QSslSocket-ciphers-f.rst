.. sip:method-description::
    :status: todo
    :pysig: e868bbe8d0b78a23048869d0175c62ad
    :realsig: () const
    :digest: d58659b4786ef928ddbb53d510901c58

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.ciphers` instead.

Returns this socket's current cryptographic cipher suite. This list is used during the socket's handshake phase for choosing a session cipher. The returned list of ciphers is ordered by descending preference. (i.e., the first cipher in the list is the most preferred cipher). The session cipher will be the first one in the list that is also supported by the peer.

By default, the handshake phase can choose any of the ciphers supported by this system's SSL libraries, which may vary from system to system. The list of ciphers supported by this system's SSL libraries is returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`. You can restrict the list of ciphers used for choosing the session cipher for this socket by calling :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCiphers` with a subset of the supported ciphers. You can revert to using the entire set by calling :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCiphers` with the list returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.

You can restrict the list of ciphers used for choosing the session cipher for *all* sockets by calling :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCiphers` with a subset of the supported ciphers. You can revert to using the entire set by calling :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCiphers` with the list returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.
