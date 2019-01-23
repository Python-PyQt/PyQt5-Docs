.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 96b67149e42c5809a1fdb454d720ed24

Stops processing audio data, preserving buffered audio data.

Sets :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.error` to :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error.NoError`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.state` to :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.SuspendedState` and emit :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.stateChanged` signal.
