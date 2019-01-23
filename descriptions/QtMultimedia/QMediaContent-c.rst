.. sip:class-description::
    :status: todo
    :brief: Access to the resources relating to a media content
    :digest: cb9249e7c680354f75a33fc84cfff280

The :sip:ref:`~PyQt5.QtMultimedia.QMediaContent` class provides access to the resources relating to a media content.

:sip:ref:`~PyQt5.QtMultimedia.QMediaContent` is used within the multimedia framework as the logical handle to media content. A :sip:ref:`~PyQt5.QtMultimedia.QMediaContent` object is composed of one or more :sip:ref:`~PyQt5.QtMultimedia.QMediaResource`\ s where each resource provides the URL and format information of a different encoding of the content.

A non-null :sip:ref:`~PyQt5.QtMultimedia.QMediaContent` will always have a primary or canonical reference to the content available through the :sip:ref:`~PyQt5.QtMultimedia.QMediaContent.canonicalUrl` or :sip:ref:`~PyQt5.QtMultimedia.QMediaContent.canonicalResource` methods, any additional resources are optional.

Alternatively :sip:ref:`~PyQt5.QtMultimedia.QMediaContent` can represent a playlist and contain a pointer to a valid :sip:ref:`~PyQt5.QtMultimedia.QMediaPlaylist` object. In this case URL is optional and can either be empty or point to the playlist URL.
