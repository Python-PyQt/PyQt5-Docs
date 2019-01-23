.. sip:class-description::
    :status: todo
    :brief: Set of video encoder settings
    :digest: b2e5fa8fc7fe34aa7b9651086bee174f

The :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings` class provides a set of video encoder settings.

A video encoder settings object is used to specify the video encoder settings used by :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder`. Video encoder settings are selected by constructing a :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings` object, setting the desired properties and then passing it to a :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder` instance using the :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.setEncodingSettings` function.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 130-134

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder`, QVideoEncoderSettingsControl.
