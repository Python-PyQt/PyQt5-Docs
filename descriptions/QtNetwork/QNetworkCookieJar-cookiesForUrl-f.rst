.. sip:method-description::
    :status: todo
    :pysig: 52ac98e9d1766c403d2baf1cb82b69e3
    :realsig: (const QUrl&) const
    :digest: 3dce71cf498abed4d947500b6225fb7b

Returns the cookies to be added to when a request is sent to *url*. This function is called by the default :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.createRequest`, which adds the cookies returned by this function to the request being sent.

If more than one cookie with the same name is found, but with differing paths, the one with longer path is returned before the one with shorter path. In other words, this function returns cookies sorted decreasingly by path length.

The default :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar` class implements only a very basic security policy (it makes sure that the cookies' domain and path match the reply's). To enhance the security policy with your own algorithms, override .

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar.setCookiesFromUrl`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.setCookieJar`.
