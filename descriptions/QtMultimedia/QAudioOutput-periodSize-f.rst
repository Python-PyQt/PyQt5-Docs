.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: d128597f580a32a3e88f1f52cfb5fbf4

Returns the period size in bytes. This is the amount of data required each period to prevent buffer underrun, and to ensure uninterrupted playback.

**Note:** It is recommended to provide at least enough data for a full period with each write operation.
