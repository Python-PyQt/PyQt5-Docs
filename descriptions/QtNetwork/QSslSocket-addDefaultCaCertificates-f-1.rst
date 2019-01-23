.. sip:method-description::
    :status: todo
    :pysig: cabffc53ddb440bd60b1e4b4c6bc9d4a
    :realsig: (const QString&,QSsl::EncodingFormat,QRegExp::PatternSyntax)
    :digest: 9800b23494318eb3b4a9b2f4a521a102

Searches all files in the *path* for certificates with the specified *encoding* and adds them to the default CA certificate database. *path* can be an explicit file, or it can contain wildcards in the format specified by *syntax*. Returns ``true`` if any CA certificates are added to the default database.

Each SSL socket's CA certificate database is initialized to the default CA certificate database.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCaCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addDefaultCaCertificate`.
