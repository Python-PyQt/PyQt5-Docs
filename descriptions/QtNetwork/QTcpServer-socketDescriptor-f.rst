.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: () const
    :digest: 01db07e6a78f8425efce64e728cd5c26

Returns the native socket descriptor the server uses to listen for incoming instructions, or -1 if the server is not listening.

If the server is using :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`, the returned descriptor may not be usable with native socket functions.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QTcpServer.setSocketDescriptor`, :sip:ref:`~PyQt5.QtNetwork.QTcpServer.isListening`.
