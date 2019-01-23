.. sip:method-description::
    :status: todo
    :pysig: c7785807f16ec998143b0a6c2ad3a183
    :realsig: (const QString&,QIODevice::OpenMode)
    :digest: 7cf30fa5f62132de0f28bb7586494c6b

This is an overloaded function.

Set the server *name* and attempts to make a connection to it.

The socket is opened in the given *openMode* and first enters :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketState.ConnectingState`. If a connection is established, :sip:ref:`~PyQt5.QtNetwork.QLocalSocket` enters :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.LocalSocketState.ConnectedState` and emits :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.connected`.

After calling this function, the socket can emit :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.error` to signal that an error occurred.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.state`, :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.serverName`, :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.waitForConnected`.
