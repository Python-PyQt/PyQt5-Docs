.. sip:method-description::
    :status: todo
    :pysig: 91ed4c18559cd4da87c24935bcadf86d
    :realsig: (const QSslCertificate&)
    :digest: ee6273b81e2e489a14f4daf4cc415001

Sets the socket's local certificate to *certificate*. The local certificate is necessary if you need to confirm your identity to the peer. It is used together with the private key; if you set the local certificate, you must also set the private key.

The local certificate and private key are always necessary for server sockets, but are also rarely used by client sockets if the server requires the client to authenticate.

**Note:** Secure Transport SSL backend on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ may update the default keychain (the default is probably your login keychain) by importing your local certificates and keys. This can also result in system dialogs showing up and asking for permission when your application is using these private keys. If such behavior is undesired, set the QT_SSL_USE_TEMPORARY_KEYCHAIN environment variable to a non-zero value; this will prompt :sip:ref:`~PyQt5.QtNetwork.QSslSocket` to use its own temporary keychain.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.localCertificate`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setPrivateKey`.
