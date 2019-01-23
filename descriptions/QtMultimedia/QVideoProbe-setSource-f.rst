.. sip:method-description::
    :status: todo
    :pysig: 8c2a7d0226abdf657c2b85e23d843288
    :realsig: (QMediaObject*)
    :digest: 40446fed4c382d415451878d37e24e83

Sets the media object to monitor to *source*.

If *source* is zero, this probe will be deactivated and this function wil return true.

If the media object does not support monitoring video, this function will return false.

Any previously monitored objects will no longer be monitored. Passing in the same object will be ignored, but monitoring will continue.
