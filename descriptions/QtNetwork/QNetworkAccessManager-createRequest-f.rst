.. sip:method-description::
    :status: todo
    :pysig: 3e4d28e519615b62fec11ee1ac883aef
    :realsig: (QNetworkAccessManager::Operation,const QNetworkRequest&,QIODevice*)
    :digest: c62fe5c52f477be597aeef5938cdabb7

Returns a new :sip:ref:`~PyQt5.QtNetwork.QNetworkReply` object to handle the operation *op* and request *originalReq*. The device *outgoingData* is always 0 for Get and Head requests, but is the value passed to :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.post` and :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.put` in those operations (the :sip:ref:`~PyQt5.QtCore.QByteArray` variants will pass a :sip:ref:`~PyQt5.QtCore.QBuffer` object).

The default implementation calls :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar.cookiesForUrl` on the cookie jar set with :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.setCookieJar` to obtain the cookies to be sent to the remote server.

The returned object must be in an open state.
