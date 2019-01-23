.. sip:class-description::
    :status: todo
    :brief: Local socket
    :digest: a7df695a5cb2f94d4d8e7dd8e37081bb

The :sip:ref:`~PyQt5.QtNetwork.QLocalSocket` class provides a local socket.

On Windows this is a named pipe and on Unix this is a local domain socket.

If an error occurs, socketError() returns the type of error, and errorString() can be called to get a human readable description of what happened.

Although :sip:ref:`~PyQt5.QtNetwork.QLocalSocket` is designed for use with an event loop, it's possible to use it without one. In that case, you must use :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.waitForConnected`, :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.waitForReadyRead`, :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.waitForBytesWritten`, and :sip:ref:`~PyQt5.QtNetwork.QLocalSocket.waitForDisconnected` which blocks until the operation is complete or the timeout expires.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QLocalServer`.
