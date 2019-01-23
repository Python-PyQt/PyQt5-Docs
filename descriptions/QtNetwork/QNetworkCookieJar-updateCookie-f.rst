.. sip:method-description::
    :status: todo
    :pysig: e6e11f6050640b73c687b6dabe51d6e0
    :realsig: (const QNetworkCookie&)
    :digest: b3d0f44c1e95ea5624fe8b52ca673412

If a cookie with the same identifier as *cookie* exists in this cookie jar it will be updated. This function uses :sip:ref:`~PyQt5.QtNetwork.QNetworkCookieJar.insertCookie`.

Returns ``true`` if *cookie* was updated, false if no cookie in the jar matches the identifier of *cookie*.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie.hasSameIdentifier`.
