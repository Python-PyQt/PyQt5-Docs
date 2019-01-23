.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: cdab58703605efd28a007f231ce1727c

Resumes processing audio data after a :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.suspend`.

Sets :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.error` to :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error.NoError`. Sets :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.state` to :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.ActiveState` if you previously called start(\ :sip:ref:`~PyQt5.QtCore.QIODevice`\*). Sets :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.state` to :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.IdleState` if you previously called :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.start`. emits :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.stateChanged` signal.
