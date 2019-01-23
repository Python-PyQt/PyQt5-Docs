.. sip:class-description::
    :status: todo
    :brief: Allows you to monitor audio being played or recorded
    :digest: ef6565c05e7d39917372fbaab4e741d2

The :sip:ref:`~PyQt5.QtMultimedia.QAudioProbe` class allows you to monitor audio being played or recorded.

::

    QAudioRecorder *recorder = new QAudioRecorder();
    QAudioProbe *probe = new QAudioProbe;

    // ... configure the audio recorder (skipped)

    connect(probe, SIGNAL(audioBufferProbed(QAudioBuffer)), this, SLOT(processBuffer(QAudioBuffer)));

    probe->setSource(recorder); // Returns true, hopefully.

    recorder->record(); // Now we can do things like calculating levels or performing an FFT

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoProbe`, :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer`, :sip:ref:`~PyQt5.QtMultimedia.QCamera`.
