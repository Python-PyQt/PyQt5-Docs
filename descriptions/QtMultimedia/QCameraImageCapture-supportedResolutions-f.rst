.. sip:method-description::
    :status: todo
    :pysig: 1e3f1bd69fd78baac6dde5fd4265e0a3
    :realsig: (const QImageEncoderSettings&,bool*) const
    :digest: bb79d4ce32966bbaec771b698889cca4

Returns a list of resolutions images can be encoded at.

If non null image *settings* parameter is passed, the returned list is reduced to resolution supported with partial settings like image codec or quality applied.

If the encoder supports arbitrary resolutions within the supported range, \*\ *continuous* is set to true, otherwise \*\ *continuous* is set to false.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QImageEncoderSettings.resolution`.
