.. sip:method-description::
    :status: todo
    :pysig: abf4bf8f09df1317f3b5577332b00392
    :realsig: () const
    :digest: 659a7d241711690683a4dfbbc49ae1f9

Returns this connection's CA certificate database. The CA certificate database is used by the socket during the handshake phase to validate the peer's certificate. It can be modified prior to the handshake with :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setCaCertificates`, or with :sip:ref:`~PyQt5.QtNetwork.QSslSocket`'s :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificate` and :sip:ref:`~PyQt5.QtNetwork.QSslSocket.addCaCertificates`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setCaCertificates`.
