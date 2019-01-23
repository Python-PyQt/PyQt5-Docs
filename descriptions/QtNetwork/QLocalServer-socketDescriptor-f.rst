.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: () const
    :digest: d5000a1f43a7a21245b112cfa35fdbed

Returns the native socket descriptor the server uses to listen for incoming instructions, or -1 if the server is not listening.

The type of the descriptor depends on the platform:

* On Windows, the returned value is a Winsock 2 Socket Handle.

* With WinRT and on INTEGRITY, the returned value is the :sip:ref:`~PyQt5.QtNetwork.QTcpServer` socket descriptor and the type is defined by :sip:ref:`~PyQt5.QtNetwork.QTcpServer.socketDescriptor`.

* On all other UNIX-like operating systems, the type is a file descriptor representing a listening socket.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QLocalServer.listen`.
