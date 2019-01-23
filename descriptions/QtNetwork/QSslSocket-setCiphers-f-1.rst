.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: f809635baf96d9cd3b91ebf9a5784dfb

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setCiphers` instead.

Sets the cryptographic cipher suite for this socket to *ciphers*, which is a colon-separated list of cipher suite names. The ciphers are listed in order of preference, starting with the most preferred cipher. For example:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_ssl_qsslsocket.py
    :lines: 100-101

Each cipher name in *ciphers* must be the name of a cipher in the list returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`. Restricting the cipher suite must be done before the handshake phase, where the session cipher is chosen.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.ciphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`.
