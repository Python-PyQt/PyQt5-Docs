.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 985ebe7b1140ec9693e7d24684d13f78

Returns is this cache should be allowed to be stored on disk.

Some cache implementations can keep these cache items in memory for performance reasons, but for security reasons they should not be written to disk.

Specifically with http, documents marked with Pragma: no-cache, or have a Cache-control set to no-store or no-cache or any https document that doesn't have "Cache-control: public" set will set the  to false.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkCacheMetaData.setSaveToDisk`.
