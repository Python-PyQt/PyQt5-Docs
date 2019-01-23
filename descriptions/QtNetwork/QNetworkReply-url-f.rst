.. sip:method-description::
    :status: todo
    :pysig: f9c1bc131cb22a5317810748e2c34038
    :realsig: () const
    :digest: d1836a920f1396db6387fe1a76174f32

Returns the URL of the content downloaded or uploaded. Note that the URL may be different from that of the original request. If the QNetworkRequest::FollowRedirectsAttribute was set in the request, then this function returns the current url that the network API is accessing, i.e the url emitted in the QNetworkReply::redirected signal.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.request`, :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.setUrl`, :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.url`.
