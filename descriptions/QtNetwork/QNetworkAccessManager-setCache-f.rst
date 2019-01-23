.. sip:method-description::
    :status: todo
    :pysig: 39deb909a192c46d734579705571bc83
    :realsig: (QAbstractNetworkCache*)
    :digest: 523076f492ed3055230706c484616b41

Sets the manager's network cache to be the *cache* specified. The cache is used for all requests dispatched by the manager.

Use this function to set the network cache object to a class that implements additional features, like saving the cookies to permanent storage.

**Note:** :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` takes ownership of the *cache* object.

:sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` by default does not have a set cache. Qt provides a simple disk cache, :sip:ref:`~PyQt5.QtNetwork.QNetworkDiskCache`, which can be used.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.cache`, :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.CacheLoadControl`.
