.. sip:method-description::
    :status: todo
    :pysig: 46a1594917962cfa4d52e1dd1f4cde00
    :realsig: (const QAudioEncoderSettings&)
    :digest: 34af9f298f4e59308e4e6b517b947c13

Sets the audio encoder *settings*.

If some parameters are not specified, or null settings are passed, the encoder will choose default encoding parameters, depending on media source properties.

It's only possible to change settings when the encoder is in the QMediaEncoder::StoppedState state.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.audioSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.videoSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.containerFormat`.
