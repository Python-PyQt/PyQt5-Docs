.. sip:method-description::
    :status: todo
    :pysig: 768db9f5ac5e66496b247636d70b1460
    :realsig: (const QAudioEncoderSettings&,bool*) const
    :digest: d244eda1ef7e1c43c4287afde29e1743

Returns a list of supported audio sample rates.

If non null audio *settings* parameter is passed, the returned list is reduced to sample rates supported with partial settings applied.

This can be used to query the list of sample rates, supported by specific audio codec.

If the encoder supports arbitrary sample rates within the supported rates range, \*\ *continuous* is set to true, otherwise \*\ *continuous* is set to false.
