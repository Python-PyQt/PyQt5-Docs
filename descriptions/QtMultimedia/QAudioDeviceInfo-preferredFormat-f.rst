.. sip:method-description::
    :status: todo
    :pysig: ea9d06a72f597a61a5addc68d9a81e52
    :realsig: () const
    :digest: 027494695585313b2070eed6a0a04f0b

Returns the default audio format settings for this device.

These settings are provided by the platform/audio plugin being used.

They are also dependent on the :sip:ref:`~PyQt5.QtMultimedia.QAudio`::Mode being used.

A typical audio system would provide something like:

* Input settings: 8000Hz mono 8 bit.

* Output settings: 44100Hz stereo 16 bit little endian.
