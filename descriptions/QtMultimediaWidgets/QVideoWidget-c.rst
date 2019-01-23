.. sip:class-description::
    :status: todo
    :brief: Widget which presents video produced by a media object
    :digest: 2baa3d7dd5a440ace86ea31105153c8e

The :sip:ref:`~PyQt5.QtMultimediaWidgets.QVideoWidget` class provides a widget which presents video produced by a media object.

Attaching a :sip:ref:`~PyQt5.QtMultimediaWidgets.QVideoWidget` to a :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` allows it to display the video or image output of that media object. A :sip:ref:`~PyQt5.QtMultimediaWidgets.QVideoWidget` is attached to media object by passing a pointer to the :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` in its constructor, and detached by destroying the :sip:ref:`~PyQt5.QtMultimediaWidgets.QVideoWidget`.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-video.py
    :lines: 147-158

**Note**: Only a single display output can be attached to a media object at one time.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`, :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer`.
