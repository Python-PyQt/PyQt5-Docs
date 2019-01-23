.. sip:method-description::
    :status: todo
    :pysig: d677f422557c9408b1c3796a2a851dba
    :realsig: ()
    :digest: 8441860ca08e81a856c0230ca473cfc4

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.caCertificates` on the default :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration` instead.

Returns the current default CA certificate database. This database is originally set to your system's default CA certificate database. If no system default database is found, an empty database will be returned. You can override the default CA certificate database with your own CA certificate database using :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCaCertificates`.

Each SSL socket's CA certificate database is initialized to the default CA certificate database.

**Note:** On Unix, this method may return an empty list if the root certificates are loaded on demand.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCaCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.caCertificates`.
