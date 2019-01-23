.. sip:method-description::
    :status: todo
    :pysig: 2798f78e00d72ed6fca9316bf104df53
    :realsig: (const QList<QSslError>&)
    :digest: 25dc476322edcd56c10edd3f1b3de63d

This is an overloaded function.

If this function is called, the SSL errors given in *errors* will be ignored.

**Note:** Because most SSL errors are associated with a certificate, for most of them you must set the expected certificate this SSL error is related to. If, for instance, you want to issue a request to a server that uses a self-signed certificate, consider the following snippet:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_access_qnetworkreply.py
    :lines: 54-61

Multiple calls to this function will replace the list of errors that were passed in previous calls. You can clear the list of errors you want to ignore by calling this function with an empty list.

**Note:** If HTTP Strict Transport Security is enabled for :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager`, this function has no effect.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.sslConfiguration`, :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.sslErrors`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.ignoreSslErrors`.
