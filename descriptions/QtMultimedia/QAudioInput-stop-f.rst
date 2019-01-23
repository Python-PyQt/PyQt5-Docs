.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: f8f6285be4689ddeacdf6940bcb9facf

Stops the audio input, detaching from the system resource.

Sets :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.error` to :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error.NoError`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.state` to :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.StoppedState` and emit :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.stateChanged` signal.
