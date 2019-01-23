.. sip:method-description::
    :status: todo
    :pysig: 33e75e552c3ff95ec78fa6a1db1d4604
    :realsig: (QMediaRecorder*)
    :digest: 09aad9ead6a31701a05415d8f0283065

Starts monitoring the given *mediaRecorder*.

If there is no mediaObject associated with *mediaRecorder*, or if it is zero, this probe will be deactivated and this function wil return true.

If the media recorder instance does not support monitoring video, this function will return false.

Any previously monitored objects will no longer be monitored. Passing in the same object will be ignored, but monitoring will continue.
