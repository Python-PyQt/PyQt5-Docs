.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: ()
    :digest: 02a7c2ee2b981bbb2d90c3afebe61364

Returns a pointer to the internal :sip:ref:`~PyQt5.QtCore.QIODevice` being used to transfer data from the system's audio input. The device will already be open and :sip:ref:`~PyQt5.QtCore.QIODevice.read` can read data directly from it.

**Note:** The pointer will become invalid after the stream is stopped or if you start another stream.

If the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` is able to access the system's audio device, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.state` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.IdleState`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.error` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error.NoError` and the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.stateChanged` signal is emitted.

If a problem occurs during this process, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.error` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error.OpenError`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.state` returns :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.StoppedState` and the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.stateChanged` signal is emitted.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QIODevice`.
