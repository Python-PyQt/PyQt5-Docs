.. sip:class-description::
    :status: todo
    :brief: TCP-based server
    :digest: 2770a7cdd4850a68b8d192960d370358

The :sip:ref:`~PyQt5.QtNetwork.QTcpServer` class provides a TCP-based server.

This class makes it possible to accept incoming TCP connections. You can specify the port or have :sip:ref:`~PyQt5.QtNetwork.QTcpServer` pick one automatically. You can listen on a specific address or on all the machine's addresses.

Call :sip:ref:`~PyQt5.QtNetwork.QTcpServer.listen` to have the server listen for incoming connections. The :sip:ref:`~PyQt5.QtNetwork.QTcpServer.newConnection` signal is then emitted each time a client connects to the server.

Call :sip:ref:`~PyQt5.QtNetwork.QTcpServer.nextPendingConnection` to accept the pending connection as a connected :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`. The function returns a pointer to a :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` in :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketState.ConnectedState` that you can use for communicating with the client.

If an error occurs, :sip:ref:`~PyQt5.QtNetwork.QTcpServer.serverError` returns the type of error, and :sip:ref:`~PyQt5.QtNetwork.QTcpServer.errorString` can be called to get a human readable description of what happened.

When listening for connections, the address and port on which the server is listening are available as :sip:ref:`~PyQt5.QtNetwork.QTcpServer.serverAddress` and :sip:ref:`~PyQt5.QtNetwork.QTcpServer.serverPort`.

Calling :sip:ref:`~PyQt5.QtNetwork.QTcpServer.close` makes :sip:ref:`~PyQt5.QtNetwork.QTcpServer` stop listening for incoming connections.

Although :sip:ref:`~PyQt5.QtNetwork.QTcpServer` is mostly designed for use with an event loop, it's possible to use it without one. In that case, you must use :sip:ref:`~PyQt5.QtNetwork.QTcpServer.waitForNewConnection`, which blocks until either a connection is available or a timeout expires.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`, `Fortune Server Example <https://doc.qt.io/qt-5/qtnetwork-fortuneserver-example.html>`_, `Threaded Fortune Server Example <https://doc.qt.io/qt-5/qtnetwork-threadedfortuneserver-example.html>`_, `Loopback Example <https://doc.qt.io/qt-5/qtnetwork-loopback-example.html>`_, `Torrent Example <https://doc.qt.io/qt-5/qtnetwork-torrent-example.html>`_.
