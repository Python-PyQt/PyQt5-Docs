.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: ()
    :digest: 928a37d8d5ef9a699b97ab3ddcd2382d

This function writes as much as possible from the internal write buffer to the underlying network socket, without blocking. If any data was written, this function returns ``true``; otherwise false is returned.

Call this function if you need :sip:ref:`~PyQt5.QtNetwork.QSslSocket` to start sending buffered data immediately. The number of bytes successfully written depends on the operating system. In most cases, you do not need to call this function, because :sip:ref:`~PyQt5.QtNetwork.QAbstractSocket` will start sending data automatically once control goes back to the event loop. In the absence of an event loop, call :sip:ref:`~PyQt5.QtNetwork.QSslSocket.waitForBytesWritten` instead.

.. seealso:: write(), :sip:ref:`~PyQt5.QtNetwork.QSslSocket.waitForBytesWritten`.
