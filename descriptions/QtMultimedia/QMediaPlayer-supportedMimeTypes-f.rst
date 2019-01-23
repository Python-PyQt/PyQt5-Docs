.. sip:method-description::
    :status: todo
    :pysig: 542b7cf81ace3e190bda636fcc7be1aa
    :realsig: (QMediaPlayer::Flags)
    :digest: f6798f9036262def3e83158d415f6bf3

Returns a list of MIME types supported by the media player.

The *flags* argument causes the resultant list to be restricted to MIME types which can be supported given additional requirements, such as performance indicators.

This function may not return useful results on some platforms, and support for a specific file of a given mime type is not guaranteed even if the mime type is in general supported. In addition, in some cases this function will need to load all available media plugins and query them for their support, which may take some time.
