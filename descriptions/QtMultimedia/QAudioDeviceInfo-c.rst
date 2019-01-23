.. sip:class-description::
    :status: todo
    :brief: Interface to query audio devices and their functionality
    :digest: e0a3f0e964d1ed9cf148770eef3dee23

The :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo` class provides an interface to query audio devices and their functionality.

:sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo` lets you query for audio devices--such as sound cards and USB headsets--that are currently available on the system. The audio devices available are dependent on the platform or audio plugins installed.

A :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo` is used by Qt to construct classes that communicate with the device--such as :sip:ref:`~PyQt5.QtMultimedia.QAudioInput`, and :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput`.

You can also query each device for the formats it supports. A format in this context is a set consisting of a specific byte order, channel, codec, frequency, sample rate, and sample type. A format is represented by the :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` class.

The values supported by the device for each of these parameters can be fetched with :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.supportedByteOrders`, :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.supportedChannelCounts`, :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.supportedCodecs`, :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.supportedSampleRates`, :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.supportedSampleSizes`, and :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.supportedSampleTypes`. The combinations supported are dependent on the platform, audio plugins installed and the audio device capabilities. If you need a specific format, you can check if the device supports it with :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.isFormatSupported`, or fetch a supported format that is as close as possible to the format with :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.nearestFormat`. For instance:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 206-214

The static functions :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.defaultInputDevice`, :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.defaultOutputDevice`, and :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.availableDevices` let you get a list of all available devices. Devices are fetched according to the value of mode this is specified by the :sip:ref:`~PyQt5.QtMultimedia.QAudio`::Mode enum. The :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo` returned are only valid for the :sip:ref:`~PyQt5.QtMultimedia.QAudio`::Mode.

For instance:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-audio.py
    :lines: 218-219

In this code sample, we loop through all devices that are able to output sound, i.e., play an audio stream in a supported format. For each device we find, we simply print the :sip:ref:`~PyQt5.QtMultimedia.QAudioDeviceInfo.deviceName`.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput`, :sip:ref:`~PyQt5.QtMultimedia.QAudioInput`.
