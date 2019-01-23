.. sip:method-description::
    :status: todo
    :pysig: 4f36a7ef363da6084155e175bfb7e5e3
    :realsig: () const
    :digest: 3133764687bcb4520b765172270a7237

Returns the current mode for the socket; either :sip:ref:`~PyQt5.QtNetwork.QSslSocket.SslMode.UnencryptedMode`, where :sip:ref:`~PyQt5.QtNetwork.QSslSocket` behaves identially to :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`, or one of :sip:ref:`~PyQt5.QtNetwork.QSslSocket.SslMode.SslClientMode` or :sip:ref:`~PyQt5.QtNetwork.QSslSocket.SslMode.SslServerMode`, where the client is either negotiating or in encrypted mode.

When the mode changes, :sip:ref:`~PyQt5.QtNetwork.QSslSocket` emits :sip:ref:`~PyQt5.QtNetwork.QSslSocket.modeChanged`

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.SslMode.SslMode`.
