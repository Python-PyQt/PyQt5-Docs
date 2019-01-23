.. sip:method-description::
    :status: todo
    :pysig: abf4bf8f09df1317f3b5577332b00392
    :realsig: () const
    :digest: 941ae41f2ff70fd57c71ef086e3ed513

Use :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.caCertificates` instead.

Returns this socket's CA certificate database. The CA certificate database is used by the socket during the handshake phase to validate the peer's certificate. It can be moodified prior to the handshake with :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificate`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificates`, and :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCaCertificates`.

**Note:** On Unix, this method may return an empty list if the root certificates are loaded on demand.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificate`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setCaCertificates`.
