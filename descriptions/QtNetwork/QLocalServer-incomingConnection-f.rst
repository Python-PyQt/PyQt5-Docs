.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: (quintptr)
    :digest: 82f5ee0c6b08e0ea879e0a006f918b1f

This virtual function is called by :sip:ref:`~PyQt5.QtNetwork.QLocalServer` when a new connection is available. *socketDescriptor* is the native socket descriptor for the accepted connection.

The base implementation creates a :sip:ref:`~PyQt5.QtNetwork.QLocalSocket`, sets the socket descriptor and then stores the :sip:ref:`~PyQt5.QtNetwork.QLocalSocket` in an internal list of pending connections. Finally :sip:ref:`~PyQt5.QtNetwork.QLocalServer.newConnection` is emitted.

Reimplement this function to alter the server's behavior when a connection is available.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QLocalServer.newConnection`, :sip:ref:`~PyQt5.QtNetwork.QLocalServer.nextPendingConnection`, :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.setSocketDescriptor`.
