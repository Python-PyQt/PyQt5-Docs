.. sip:method-description::
    :status: todo
    :pysig: bb5fd9ce345b1d02ebd75dbd068cb0b0
    :realsig: (const QList<QNetworkCookie>&)
    :digest: 77fbb41f70f489ae6e33c710811a7836

Sets the internal list of cookies held by this cookie jar to be *cookieList*. This function is suitable for derived classes to implement loading cookies from permanent storage, or their own cookie acceptance policies by reimplementing :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar.setCookiesFromUrl`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar.allCookies`, :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar.setCookiesFromUrl`.
