.. sip:method-description::
    :status: todo
    :pysig: 3f4136c9474647a00455a685479b1fcf
    :realsig: (const QUrl&,const char*)
    :digest: 69cc38d7f987620ae3abc010da364783

Load playlist from *location*. If *format* is specified, it is used, otherwise format is guessed from location name and data.

New items are appended to playlist.

:sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.loaded` signal is emitted if playlist was loaded successfully, otherwise the playlist emits :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.loadFailed`.
