.. sip:class-description::
    :status: todo
    :brief: Allows you to monitor video frames being played or recorded
    :digest: a7daea208b698648904a571332378bc0

The :sip:ref:`~PyQt5.QtMultimedia.QVideoProbe` class allows you to monitor video frames being played or recorded.

::

    QMediaPlayer *player = new QMediaPlayer();
    QVideoProbe *probe = new QVideoProbe;

    connect(probe, SIGNAL(videoFrameProbed(QVideoFrame)), this, SLOT(processFrame(QVideoFrame)));

    probe->setSource(player); // Returns true, hopefully.

    player->setVideoOutput(myVideoSurface);
    player->setMedia(QUrl::fromLocalFile("observation.mp4"));
    player->play(); // Start receiving frames as they get presented to myVideoSurface

This same approach works with the :sip:ref:`~PyQt5.QtMultimedia.QCamera` object as well, to receive viewfinder or video frames as they are captured.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioProbe`, :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer`, :sip:ref:`~PyQt5.QtMultimedia.QCamera`.
