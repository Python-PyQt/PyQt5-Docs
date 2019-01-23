.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 5b9bb331702d0c6f65dada463bfb60df

Sets the media *container* format.

If the container format is not specified, the encoder will choose format, depending on media source properties and encoding settings selected.

It's only possible to change settings when the encoder is in the QMediaEncoder::StoppedState state.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.audioSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.videoSettings`, :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.containerFormat`.
