.. sip:method-description::
    :status: todo
    :pysig: 8c8a27afd980e93a79844064bde098d8
    :realsig: (const QVideoEncoderSettings&)
    :digest: f68c5de2645371f0a0fe223cf6eaf59c

Sets the video encoder *settings*.

If some parameters are not specified, or null settings are passed, the encoder will choose default encoding parameters, depending on media source properties.

It's only possible to change settings when the encoder is in the QMediaEncoder::StoppedState state.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.audioSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.videoSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.containerFormat`.
