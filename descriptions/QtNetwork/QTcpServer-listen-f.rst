.. sip:method-description::
    :status: todo
    :pysig: 85e0b23c5d5fd5c6c86acdc7ba31dbfe
    :realsig: (const QHostAddress&,quint16)
    :digest: 137dd2dbef5040853b0e0b69c6f5838d

Tells the server to listen for incoming connections on address *address* and port *port*. If *port* is 0, a port is chosen automatically. If *address* is :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress.Any`, the server will listen on all network interfaces.

Returns ``true`` on success; otherwise returns ``false``.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QTcpServer.isListening`.
