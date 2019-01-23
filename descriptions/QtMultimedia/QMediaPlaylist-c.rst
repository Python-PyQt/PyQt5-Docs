.. sip:class-description::
    :status: todo
    :brief: List of media content to play
    :digest: 7d275aa5e2f7209a582be34d5e91da2e

The :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist` class provides a list of media content to play.

:sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist` is intended to be used with other media objects, like :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer`.

:sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist` allows to access the service intrinsic playlist functionality if available, otherwise it provides the local memory playlist implementation.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 179-192

Depending on playlist source implementation, most of the playlist mutating operations can be asynchronous.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`.
