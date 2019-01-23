.. sip:method-description::
    :status: todo
    :pysig: c5678c117ef46f2f326b91e0efbb241c
    :realsig: (const QString&,QSsl::EncodingFormat,QRegExp::PatternSyntax)
    :digest: 0a6418386c806fea2e52ba931016a460

Searches all files in the *path* for certificates encoded in the specified *format* and adds them to this socket's CA certificate database. *path* must be a file or a pattern matching one or more files, as specified by *syntax*. Returns ``true`` if one or more certificates are added to the socket's CA certificate database; otherwise returns ``false``.

The CA certificate database is used by the socket during the handshake phase to validate the peer's certificate.

For more precise control, use :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificate`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificate`.
