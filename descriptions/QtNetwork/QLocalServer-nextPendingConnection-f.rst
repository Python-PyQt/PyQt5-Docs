.. sip:method-description::
    :status: todo
    :pysig: 9aad412180eb0183f0a90260657b823e
    :realsig: ()
    :digest: 6988f2d03812e949ef5fb2e977025c79

Returns the next pending connection as a connected :sip:ref:`~PyQt5.QtNetwork.QLocalSocket` object.

The socket is created as a child of the server, which means that it is automatically deleted when the :sip:ref:`~PyQt5.QtNetwork.QLocalServer` object is destroyed. It is still a good idea to delete the object explicitly when you are done with it, to avoid wasting memory.

0 is returned if this function is called when there are no pending connections.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QLocalServer.hasPendingConnections`, :sip:ref:`~PyQt5.QtNetwork.QLocalServer.newConnection`, :sip:ref:`~PyQt5.QtNetwork.QLocalServer.incomingConnection`.
