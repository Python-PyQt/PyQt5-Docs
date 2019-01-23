.. sip:method-description::
    :status: todo
    :pysig: 2798f78e00d72ed6fca9316bf104df53
    :realsig: (const QList<QSslError>&)
    :digest: 1cfe57754bc033434d2dc2ad9902e39e

This is an overloaded function.

This method tells :sip:ref:`~PyQt5.QtNetwork.QSslSocket` to ignore only the errors given in *errors*.

**Note:** Because most SSL errors are associated with a certificate, for most of them you must set the expected certificate this SSL error is related to. If, for instance, you want to connect to a server that uses a self-signed certificate, consider the following snippet:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_ssl_qsslsocket.py
    :lines: 112-119

Multiple calls to this function will replace the list of errors that were passed in previous calls. You can clear the list of errors you want to ignore by calling this function with an empty list.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.sslErrors`.
