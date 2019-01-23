.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: 1f1f9f79b55b1acec90c4c029647bfe2

Sets the interval for :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.notify` signal to be emitted. This is based on the *ms* of audio data processed not on actual real-time. The minimum resolution of the timer is platform specific and values should be checked with :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.notifyInterval` to confirm actual value being used.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.notifyInterval`.
