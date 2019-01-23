.. sip:method-description::
    :status: todo
    :pysig: a3fbb698784d4f3a1fd0b4413db7e756
    :realsig: (const QAudioFormat&) const
    :digest: c724d4e879aed9ac399beb270f436d05

Returns the closest :sip:ref:`~PyQt5.QtMultimedia.QAudioFormat` to the supplied *settings* that the system supports.

These settings are provided by the platform/audio plugin being used.

They are also dependent on the :sip:ref:`~PyQt5.QtMultimedia.QAudio`::Mode being used.
