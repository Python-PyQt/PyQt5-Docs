.. sip:class-description::
    :status: todo
    :brief: Description of a media resource
    :digest: eb12d733819195a3355e6e33ceb35c61

The :sip:ref:`~PyQt5.QtMultimedia.QMediaResource` class provides a description of a media resource.

A media resource is composed of a :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.url` containing the location of the resource and a set of properties that describe the format of the resource. The properties provide a means to assess a resource without first attempting to load it, and in situations where media be represented by multiple alternative representations provide a means to select the appropriate resource.

Media made available by a remote services can often be available in multiple encodings or quality levels, this allows a client to select an appropriate resource based on considerations such as codecs supported, network bandwidth, and display constraints. :sip:ref:`~PyQt5.QtMultimedia.QMediaResource` includes information such as the :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.mimeType`, :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.audioCodec` and :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.videoCodec` codecs, :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.audioBitRate` and :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.videoBitRate` bit rates, and :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.resolution` so these constraints and others can be evaluated.

The only mandatory property of a :sip:ref:`~PyQt5.QtMultimedia.QMediaResource` is the :sip:ref:`~PyQt5.QtMultimedia.QMediaResource.url`.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaContent`.
