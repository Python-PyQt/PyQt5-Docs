.. sip:method-description::
    :status: todo
    :pysig: ab999e9ba1e86adf0437a8843bff363b
    :realsig: (QNetworkCookie::RawForm) const
    :digest: f1ab2c2458636f27deda5c91a97c0a18

Returns the raw form of this :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie`. The :sip:ref:`~PyQt5.QtCore.QByteArray` returned by this function is suitable for an HTTP header, either in a server response (the Set-Cookie header) or the client request (the Cookie header). You can choose from one of two formats, using *form*.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie.parseCookies`.
