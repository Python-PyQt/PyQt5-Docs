.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: () const
    :digest: 5c3c6d9d24c8d020a25cd42f6b5d0f7a

Returns a pointer to the native key handle, if it is available; otherwise a null pointer is returned.

You can use this handle together with the native API to access extended information about the key.

**Warning:** Use of this function has a high probability of being non-portable, and its return value may vary across platforms, and between minor Qt releases.
