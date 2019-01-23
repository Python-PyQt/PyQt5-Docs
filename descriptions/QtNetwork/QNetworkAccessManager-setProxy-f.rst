.. sip:method-description::
    :status: todo
    :pysig: 946235c4017d4af089af1ab5dabf4d8e
    :realsig: (const QNetworkProxy&)
    :digest: 336f697cef3992ba37488f1ae7a45a11

Sets the proxy to be used in future requests to be *proxy*. This does not affect requests that have already been sent. The :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.proxyAuthenticationRequired` signal will be emitted if the proxy requests authentication.

A proxy set with this function will be used for all requests issued by :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager`. In some cases, it might be necessary to select different proxies depending on the type of request being sent or the destination host. If that's the case, you should consider using :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.setProxyFactory`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.proxy`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.proxyAuthenticationRequired`.
