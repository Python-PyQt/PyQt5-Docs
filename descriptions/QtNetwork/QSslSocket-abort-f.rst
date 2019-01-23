.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: b9e35d7b56624305f17d5eef417364eb

Aborts the current connection and resets the socket. Unlike :sip:ref:`~PyQt5.QtNetwork.QSslSocket.disconnectFromHost`, this function immediately closes the socket, clearing any pending data in the write buffer.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.disconnectFromHost`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.close`.
