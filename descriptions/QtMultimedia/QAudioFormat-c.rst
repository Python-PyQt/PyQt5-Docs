.. sip:class-description::
    :status: todo
    :brief: Stores audio stream parameter information
    :digest: 6593cf8046e60b16d944865d388ba0bd

The :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` class stores audio stream parameter information.

An audio format specifies how data in an audio stream is arranged, i.e, how the stream is to be interpreted. The encoding itself is specified by the :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat.codec` used for the stream.

In addition to the encoding, :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` contains other parameters that further specify how the audio sample data is arranged. These are the frequency, the number of channels, the sample size, the sample type, and the byte order. The following table describes these in more detail.

+--------------------+------------------------------------------------------------------------------------------+
| Parameter          | Description                                                                              |
+====================+==========================================================================================+
| Sample Rate        | Samples per second of audio data in Hertz.                                               |
+--------------------+------------------------------------------------------------------------------------------+
| Number of channels | The number of audio channels (typically one for mono or two for stereo)                  |
+--------------------+------------------------------------------------------------------------------------------+
| Sample size        | How much data is stored in each sample (typically 8 or 16 bits)                          |
+--------------------+------------------------------------------------------------------------------------------+
| Sample type        | Numerical representation of sample (typically signed integer, unsigned integer or float) |
+--------------------+------------------------------------------------------------------------------------------+
| Byte order         | Byte ordering of sample (typically little endian, big endian)                            |
+--------------------+------------------------------------------------------------------------------------------+

This class is typically used in conjunction with :sip:ref:`~PyQt5.QtMultimedia.QAudioInput` or :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` to allow you to specify the parameters of the audio stream being read or written, or with :sip:ref:`~PyQt5.QtMultimedia.QAudioBuffer` when dealing with samples in memory.

You can obtain audio formats compatible with the audio device used through functions in :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo`. This class also lets you query available parameter values for a device, so that you can set the parameters yourself. See the :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo` class description for details. You need to know the format of the audio streams you wish to play or record.

In the common case of interleaved linear PCM data, the codec will be "audio/pcm", and the samples for all channels will be interleaved. One sample for each channel for the same instant in time is referred to as a frame in Qt Multimedia (and other places).
