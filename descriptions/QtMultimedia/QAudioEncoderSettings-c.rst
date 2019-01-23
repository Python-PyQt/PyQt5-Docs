.. sip:class-description::
    :status: todo
    :brief: Set of audio encoder settings
    :digest: 2745172dea860345f42560b81d34d575

The :sip:ref:`~PyQt5.QtMultimedia.QAudioEncoderSettings` class provides a set of audio encoder settings.

A audio encoder settings object is used to specify the audio encoder settings used by :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder`. Audio encoder settings are selected by constructing a :sip:ref:`~PyQt5.QtMultimedia.QAudioEncoderSettings` object, setting the desired properties and then passing it to a :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder` instance using the :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.setEncodingSettings` function.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 122-126

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder`, QAudioEncoderSettingsControl.
