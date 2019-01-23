.. sip:method-description::
    :status: todo
    :pysig: 8c2a7d0226abdf657c2b85e23d843288
    :realsig: (QMediaObject*)
    :digest: 19e6c026634f17b8b2592241d0c535e3

Sets the media object to monitor to *source*.

If *source* is zero, this probe will be deactivated and this function wil return true.

If the media object does not support monitoring audio, this function will return false.

The previous object will no longer be monitored. Passing in the same object will be ignored, but monitoring will continue.
