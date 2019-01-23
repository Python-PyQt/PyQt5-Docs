.. sip:method-description::
    :status: todo
    :pysig: 4ebcca4b876ddf43aac5582e04e14a68
    :realsig: (int)
    :digest: f69d5c38818932a8e0d69e2cf6b4d830

Waits until the socket has completed the SSL handshake and has emitted :sip:ref:`~PyQt5.QtNetwork.QSslSocket.encrypted`, or *msecs* milliseconds, whichever comes first. If :sip:ref:`~PyQt5.QtNetwork.QSslSocket.encrypted` has been emitted, this function returns true; otherwise (e.g., the socket is disconnected, or the SSL handshake fails), false is returned.

The following example waits up to one second for the socket to be encrypted:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_ssl_qsslsocket.py
    :lines: 106-108

If msecs is -1, this function will not time out.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.startClientEncryption`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.startServerEncryption`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.encrypted`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.isEncrypted`.
