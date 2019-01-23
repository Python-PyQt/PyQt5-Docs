.. sip:method-description::
    :status: todo
    :pysig: 7815ad049d0eb587d7f38efbf798236e
    :realsig: (int,const QAudioFormat&,qint64)
    :digest: 86b6583ad2ece0f88c110b4a204c477f

Creates a new audio buffer with space for *numFrames* frames of the given *format*. The individual samples will be initialized to the default for the format.

*startTime* (in microseconds) indicates when this buffer starts in the stream. If this buffer is not part of a stream, set it to -1.
