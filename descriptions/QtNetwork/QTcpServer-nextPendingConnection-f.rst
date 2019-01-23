.. sip:method-description::
    :status: todo
    :pysig: 7c99b10a523615dc8a997ec407f32220
    :realsig: ()
    :digest: 406a85abbc9ef7538554361d3d053b67

Returns the next pending connection as a connected :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` object.

The socket is created as a child of the server, which means that it is automatically deleted when the :sip:ref:`~PyQt5.QtNetwork.QTcpServer` object is destroyed. It is still a good idea to delete the object explicitly when you are done with it, to avoid wasting memory.

0 is returned if this function is called when there are no pending connections.

**Note:** The returned :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` object cannot be used from another thread. If you want to use an incoming connection from another thread, you need to override :sip:ref:`~PyQt5.QtNetwork.QTcpServer.incomingConnection`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QTcpServer.hasPendingConnections`.
