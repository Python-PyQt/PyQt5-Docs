.. sip:method-description::
    :status: todo
    :pysig: b37aad6e532307d92dc1d1e337e5f869
    :realsig: (const QVideoEncoderSettings&,bool*) const
    :digest: 91b92768f850f390c76af5607adc7356

Returns a list of frame rates video can be encoded at.

If non null video *settings* parameter is passed, the returned list is reduced to frame rates supported with partial settings like video codec or resolution applied.

If the encoder supports arbitrary frame rates within the supported range, \*\ *continuous* is set to true, otherwise \*\ *continuous* is set to false.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoEncoderSettings.frameRate`.
