.. sip:method-description::
    :status: todo
    :pysig: ed144c95b536a5a3021c7132a25b2753
    :realsig: (const QVideoEncoderSettings&,bool*) const
    :digest: a4f0eb714645c59452d2e00069289491

Returns a list of resolutions video can be encoded at.

If non null video *settings* parameter is passed, the returned list is reduced to resolution supported with partial settings like video codec or framerate applied.

If the encoder supports arbitrary resolutions within the supported range, \*\ *continuous* is set to true, otherwise \*\ *continuous* is set to false.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings.resolution`.
