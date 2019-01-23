.. sip:class-description::
    :status: todo
    :brief: Interface for receiving audio data from an audio input device
    :digest: c33a6c894a67000c9462fa5a1ae95efe

The :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` class provides an interface for receiving audio data from an audio input device.

You can construct an audio input with the system's :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.defaultInputDevice`. It is also possible to create :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` with a specific :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo`. When you create the audio input, you should also send in the :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` to be used for the recording (see the :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` class description for details).

To record to a file:

:sip:ref:`~PyQt5.QtMultimedia.QAudioInput` lets you record audio with an audio input device. The default constructor of this class will use the systems default audio device, but you can also specify a :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo` for a specific device. You also need to pass in the :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` in which you wish to record.

Starting up the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` is simply a matter of calling :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.start` with a :sip:ref:`~PyQt5.QtCore.QIODevice` opened for writing. For instance, to record to a file, you can:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 66-67

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 74-99

This will start recording if the format specified is supported by the input device (you can check this with :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.isFormatSupported`. In case there are any snags, use the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.error` function to check what went wrong. We stop recording in the ``stopRecording()`` slot.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 103-108

At any point in time, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` will be in one of four states: active, suspended, stopped, or idle. These states are specified by the :sip:ref:`~PyQt5.QtMultimedia.QAudio.State` enum. You can request a state change directly through :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.suspend`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.resume`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.stop`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.reset`, and :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.start`. The current state is reported by :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.state`. :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` will also signal you when the state changes (\ :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.stateChanged`).

:sip:ref:`~PyQt5.QtMultimedia.QAudioInput` provides several ways of measuring the time that has passed since the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.start` of the recording. The ``processedUSecs()`` function returns the length of the stream in microseconds written, i.e., it leaves out the times the audio input was suspended or idle. The :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.elapsedUSecs` function returns the time elapsed since :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.start` was called regardless of which states the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` has been in.

If an error should occur, you can fetch its reason with :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.error`. The possible error reasons are described by the :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error` enum. The :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` will enter the :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.StoppedState` when an error is encountered. Connect to the :sip:ref:`~PyQt5.QtMultimedia.QAudioInput.stateChanged` signal to handle the error:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 112-131

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput`, :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo`.
