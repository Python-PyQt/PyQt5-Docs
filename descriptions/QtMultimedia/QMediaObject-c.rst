.. sip:class-description::
    :status: todo
    :brief: Common base for multimedia objects
    :digest: db0786340e1219c5dee4bc010cca46bb

The :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` class provides a common base for multimedia objects.

It provides some basic functionality that is common to other high level classes like :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer`, QAudioDecoder and :sip:ref:`~PyQt5.QtMultimedia.QCamera`, including availability and meta-data functionality, as well as functionality to connect media objects with support classes like :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist`.

The higher level :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` derived classes provide the actual multimedia functionality, by internally using a :sip:ref:`~PyQt5.QtMultimedia.QMediaService`. Each media object hosts a :sip:ref:`~PyQt5.QtMultimedia.QMediaService` and uses the :sip:ref:`~PyQt5.QtMultimedia.QMediaControl` interfaces implemented by the service to implement its API. These controls can be accessed from the media object if necessary, but in general the useful functionality can be accessed from the higher level classes.

Most media objects when constructed will request a new :sip:ref:`~PyQt5.QtMultimedia.QMediaService` instance, but some like :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder` and :sip:ref:`~PyQt5.QtMultimedia.QAudioRecorder` will share a service with another object.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaService`, :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`.
