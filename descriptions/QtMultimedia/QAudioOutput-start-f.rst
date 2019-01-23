.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: ()
    :digest: b934394de373371d046c45bbf992a17a

Returns a pointer to the internal :sip:ref:`~PyQt5.QtCore.QIODevice` being used to transfer data to the system's audio output. The device will already be open and :sip:ref:`~PyQt5.QtCore.QIODevice.write` can write data directly to it.

**Note:** The pointer will become invalid after the stream is stopped or if you start another stream.

If the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` is able to access the system's audio device, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.state` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.IdleState`, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.error` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error.NoError` and the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.stateChanged` signal is emitted.

If a problem occurs during this process, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.error` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error.OpenError`, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.state` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.StoppedState` and the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.stateChanged` signal is emitted.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QIODevice`.
