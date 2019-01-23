.. sip:method-description::
    :status: todo
    :pysig: 946235c4017d4af089af1ab5dabf4d8e
    :realsig: (const QNetworkProxy&)
    :digest: 2797298ddadd968d707230ab69770b6c

Sets the explicit network proxy for this socket to *networkProxy*.

To disable the use of a proxy for this socket, use the :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy.ProxyType.NoProxy` proxy type:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_socket_qtcpserver.py
    :lines: 54-54

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QTcpServer.proxy`, :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`.
