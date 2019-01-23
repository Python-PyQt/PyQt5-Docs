.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: ()
    :digest: d761d14310f8b8fa73d64d185bf0fa56

Returns a pointer to this buffer's data. You can modify the data through the returned pointer.

Since QAudioBuffers can share the actual sample data, calling this function will result in a deep copy being made if there are any other buffers using the sample. You should avoid calling this unless you really need to modify the data.

This pointer will remain valid until the underlying storage is detached. In particular, if you obtain a pointer, and then copy this audio buffer, changing data through this pointer may change both buffer instances. Calling :sip:ref:`~PyQt5.QtMultimedia.QAudioBuffer.data` on either instance will again cause a deep copy to be made, which may invalidate the pointers returned from this function previously.

There is also a templatized version of :sip:ref:`~PyQt5.QtMultimedia.QAudioBuffer.data` allows you to retrieve a specific type of pointer to the data. Note that there is no checking done on the format of the audio buffer - this is simply a convenience function.

::

    // With a 16bit sample buffer:
    quint16 *data = buffer->data<quint16>(); // May cause deep copy
