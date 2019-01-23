.. sip:class-description::
    :status: todo
    :brief: Allows the playing of a media source
    :digest: f17bb4aabca82eba243665767ea3ff4b

The :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer` class allows the playing of a media source.

The :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer` class is a high level media playback class. It can be used to playback such content as songs, movies and internet radio. The content to playback is specified as a :sip:ref:`~PyQt5.QtMultimedia.QMediaContent` object, which can be thought of as a main or canonical URL with additional information attached. When provided with a :sip:ref:`~PyQt5.QtMultimedia.QMediaContent` playback may be able to commence.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 152-156

:sip:ref:`~PyQt5.QtMultimediaWidgets.QVideoWidget` can be used with :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer` for video rendering and :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist` for accessing playlist functionality.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 179-192

Since :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer` is a :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`, you can use several of the :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` functions for things like:

* Accessing the currently playing media's metadata (\ :sip:ref:`~PyQt5.QtMultimedia.QMediaObject.metaData` and :sip:ref:`~PyQt5.QtMultimedia.QMediaMetaData`)

* Checking to see if the media playback service is currently available (\ :sip:ref:`~PyQt5.QtMultimedia.QMediaObject.availability`)

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`, :sip:ref:`~PyQt5.QtMultimedia.QMediaService`, :sip:ref:`~PyQt5.QtMultimediaWidgets.QVideoWidget`, :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist`.
