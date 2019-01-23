.. sip:method-description::
    :status: todo
    :pysig: e6e11f6050640b73c687b6dabe51d6e0
    :realsig: (const QNetworkCookie&)
    :digest: 1c325a6e31119aa7af04769ba4fef700

Adds *cookie* to this cookie jar.

Returns ``true`` if *cookie* was added, false otherwise.

If a cookie with the same identifier already exists in the cookie jar, it will be overridden.
