.. sip:method-description::
    :status: todo
    :pysig: a373c99d52d63a379397a2afc23a5b0b
    :realsig: (const QList<QSslCertificate>&)
    :digest: dbdd9f982042cee4804aa676f8aaa138

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setCaCertificates` on the default :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration` instead.

Sets the default CA certificate database to *certificates*. The default CA certificate database is originally set to your system's default CA certificate database. You can override the default CA certificate database with your own CA certificate database using this function.

Each SSL socket's CA certificate database is initialized to the default CA certificate database.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCaCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addDefaultCaCertificate`.
