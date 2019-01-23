.. sip:method-description::
    :status: todo
    :pysig: 74a283d09733a946a8e30017016b5227
    :realsig: (const QSslKey&)
    :digest: 3de50beb23e0612be4ea38b5e72a49fd

Sets the socket's private :sip:ref:`~PyQt5.QtNetwork.QSslKey` to *key*. The private key and the local :sip:ref:`~PyQt5.QtNetwork.QSslCertificate` are used by clients and servers that must prove their identity to SSL peers.

Both the key and the local certificate are required if you are creating an SSL server socket. If you are creating an SSL client socket, the key and local certificate are required if your client must identify itself to an SSL server.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.privateKey`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setLocalCertificate`.
