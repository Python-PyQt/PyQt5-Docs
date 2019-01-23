.. sip:class-description::
    :status: todo
    :brief: TCP socket
    :digest: cec3ab99b34dea52afb7880e13e02acc

The :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` class provides a TCP socket.

TCP (Transmission Control Protocol) is a reliable, stream-oriented, connection-oriented transport protocol. It is especially well suited for continuous transmission of data.

:sip:ref:`~PyQt5.QtNetwork.QTcpSocket` is a convenience subclass of :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket` that allows you to establish a TCP connection and transfer streams of data. See the :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket` documentation for details.

**Note:** TCP sockets cannot be opened in :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.Unbuffered` mode.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QTcpServer`, :sip:ref:`~PyQt5.QtNetwork.QUdpSocket`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager`, `Fortune Server Example <https://doc.qt.io/qt-5/qtnetwork-fortuneserver-example.html>`_, `Fortune Client Example <https://doc.qt.io/qt-5/qtnetwork-fortuneclient-example.html>`_, `Threaded Fortune Server Example <https://doc.qt.io/qt-5/qtnetwork-threadedfortuneserver-example.html>`_, `Blocking Fortune Client Example <https://doc.qt.io/qt-5/qtnetwork-blockingfortuneclient-example.html>`_, `Loopback Example <https://doc.qt.io/qt-5/qtnetwork-loopback-example.html>`_, `Torrent Example <https://doc.qt.io/qt-5/qtnetwork-torrent-example.html>`_.
