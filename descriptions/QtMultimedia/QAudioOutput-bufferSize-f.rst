.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 286469094045c502524c18b02b86bc43

Returns the audio buffer size in bytes.

If called before :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.start`, returns platform default value. If called before :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.start` but :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.setBufferSize` was called prior, returns value set by :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.setBufferSize`. If called after :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.start`, returns the actual buffer size being used. This may not be what was set previously by :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.setBufferSize`.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.setBufferSize`.
