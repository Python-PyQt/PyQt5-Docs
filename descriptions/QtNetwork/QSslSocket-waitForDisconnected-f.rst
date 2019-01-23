.. sip:method-description::
    :status: todo
    :pysig: 4ebcca4b876ddf43aac5582e04e14a68
    :realsig: (int)
    :digest: a214973eaeb48faf3b3c40235f493fe7

Waits until the socket has disconnected or *msecs* milliseconds, whichever comes first. If the connection has been disconnected, this function returns ``true``; otherwise it returns ``false``.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket.waitForDisconnected`.
