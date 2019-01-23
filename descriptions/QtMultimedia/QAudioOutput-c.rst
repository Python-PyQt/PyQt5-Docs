.. sip:class-description::
    :status: todo
    :brief: Interface for sending audio data to an audio output device
    :digest: f9c5997020c1c0444d89d861210d797d

The :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` class provides an interface for sending audio data to an audio output device.

You can construct an audio output with the system's :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.defaultOutputDevice`. It is also possible to create :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` with a specific :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo`. When you create the audio output, you should also send in the :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` to be used for the playback (see the :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` class description for details).

To play a file:

Starting to play an audio stream is simply a matter of calling :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.start` with a :sip:ref:`~PyQt5.QtCore.QIODevice`. :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` will then fetch the data it needs from the io device. So playing back an audio file is as simple as:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 145-146

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 153-175

The file will start playing assuming that the audio system and output device support it. If you run out of luck, check what's up with the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.error` function.

After the file has finished playing, we need to stop the device:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 179-200

At any given time, the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` will be in one of four states: active, suspended, stopped, or idle. These states are described by the :sip:ref:`~PyQt5.QtMultimedia.QAudio.State` enum. State changes are reported through the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.stateChanged` signal. You can use this signal to, for instance, update the GUI of the application; the mundane example here being changing the state of a ``play/pause`` button. You request a state change directly with :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.suspend`, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.stop`, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.reset`, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.resume`, and :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.start`.

While the stream is playing, you can set a notify interval in milliseconds with :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.setNotifyInterval`. This interval specifies the time between two emissions of the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.notify` signal. This is relative to the position in the stream, i.e., if the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` is in the SuspendedState or the IdleState, the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.notify` signal is not emitted. A typical use-case would be to update a slider that allows seeking in the stream. If you want the time since playback started regardless of which states the audio output has been in, :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.elapsedUSecs` is the function for you.

If an error occurs, you can fetch the :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error` with the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.error` function. Please see the :sip:ref:`~PyQt5.QtMultimedia.QAudio.Error` enum for a description of the possible errors that are reported. When an error is encountered, the state changes to :sip:ref:`~PyQt5.QtMultimedia.QAudio.State.StoppedState`. You can check for errors by connecting to the :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.stateChanged` signal:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 179-200

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioInput`, :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo`.
