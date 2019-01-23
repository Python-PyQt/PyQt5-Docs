.. sip:method-description::
    :status: todo
    :pysig: 3907bf992d778296c469039b3fedb4b4
    :realsig: (QSsl::SslProtocol)
    :digest: 720cda0367c7855acf039677a1945961

Sets the socket's SSL protocol to *protocol*. This will affect the next initiated handshake; calling this function on an already-encrypted socket will not affect the socket's protocol.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.protocol`.
