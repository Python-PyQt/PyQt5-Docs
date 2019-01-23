.. sip:method-description::
    :status: todo
    :pysig: 9a1511061613ba596c7092cf28a3693f
    :realsig: (QIODevice*,const char*)
    :digest: db91d01dfd49715fc71120a4eb0aa529

Load playlist from :sip:ref:`~PyQt5.QtCore.QIODevice` *device*. If *format* is specified, it is used, otherwise format is guessed from device data.

New items are appended to playlist.

:sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.loaded` signal is emitted if playlist was loaded successfully, otherwise the playlist emits :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist.loadFailed`.
