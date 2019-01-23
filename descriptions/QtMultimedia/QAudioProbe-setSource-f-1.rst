.. sip:method-description::
    :status: todo
    :pysig: 33e75e552c3ff95ec78fa6a1db1d4604
    :realsig: (QMediaRecorder*)
    :digest: ce44e488096912709c78cb5afdfccc51

Starts monitoring the given *mediaRecorder*.

Returns true on success.

If there is no mediaObject associated with *mediaRecorder*, or if it is zero, this probe will be deactivated and this function wil return true.

If the media recorder instance does not support monitoring audio, this function will return false.

Any previously monitored objects will no longer be monitored. Passing in the same (valid) object will be ignored, but monitoring will continue.
