.. sip:class-description::
    :status: todo
    :brief: UDP socket
    :digest: 49659e6c2f7f3ee19100d5a29a80d607

The :sip:ref:`~PyQt5.QtNetwork.QUdpSocket` class provides a UDP socket.

UDP (User Datagram Protocol) is a lightweight, unreliable, datagram-oriented, connectionless protocol. It can be used when reliability isn't important. :sip:ref:`~PyQt5.QtNetwork.QUdpSocket` is a subclass of :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket` that allows you to send and receive UDP datagrams.

The most common way to use this class is to bind to an address and port using bind(), then call :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.writeDatagram` and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.readDatagram` / :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.receiveDatagram` to transfer data. If you want to use the standard :sip:ref:`~PyQt5.QtCore.QIODevice` functions read(), readLine(), write(), etc., you must first connect the socket directly to a peer by calling connectToHost().

The socket emits the bytesWritten() signal every time a datagram is written to the network. If you just want to send datagrams, you don't need to call bind().

The readyRead() signal is emitted whenever datagrams arrive. In that case, :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.hasPendingDatagrams` returns ``true``. Call :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.pendingDatagramSize` to obtain the size of the first pending datagram, and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.readDatagram` or :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.receiveDatagram` to read it.

**Note:** An incoming datagram should be read when you receive the readyRead() signal, otherwise this signal will not be emitted for the next datagram.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_socket_qudpsocket.py
    :lines: 54-69

:sip:ref:`~PyQt5.QtNetwork.QUdpSocket` also supports UDP multicast. Use :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.joinMulticastGroup` and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.leaveMulticastGroup` to control group membership, and :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketOption.MulticastTtlOption` and :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.SocketOption.MulticastLoopbackOption` to set the TTL and loopback socket options. Use :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.setMulticastInterface` to control the outgoing interface for multicast datagrams, and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket.multicastInterface` to query it.

With :sip:ref:`~PyQt5.QtNetwork.QUdpSocket`, you can also establish a virtual connection to a UDP server using connectToHost() and then use read() and write() to exchange datagrams without specifying the receiver for each datagram.

The `Broadcast Sender <https://doc.qt.io/qt-5/qtnetwork-broadcastsender-example.html>`_, `Broadcast Receiver <https://doc.qt.io/qt-5/qtnetwork-broadcastreceiver-example.html>`_, `Multicast Sender <https://doc.qt.io/qt-5/qtnetwork-multicastsender-example.html>`_, and `Multicast Receiver <https://doc.qt.io/qt-5/qtnetwork-multicastreceiver-example.html>`_ examples illustrate how to use :sip:ref:`~PyQt5.QtNetwork.QUdpSocket` in applications.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`, :sip:ref:`~PyQt5.QtNetwork.QNetworkDatagram`.
