.. sip:method-description::
    :status: todo
    :pysig: 02317439f246178ae8a84bf3264e266e
    :realsig: (const QAudioEncoderSettings&,const QVideoEncoderSettings&,const QString&)
    :digest: 8aaab9b8dbe68db5ae1390b064914d8a

Sets the *audio* and *video* encoder settings and *container* format.

If some parameters are not specified, or null settings are passed, the encoder will choose default encoding parameters, depending on media source properties.

It's only possible to change settings when the encoder is in the QMediaEncoder::StoppedState state.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.audioSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.videoSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.containerFormat`.
