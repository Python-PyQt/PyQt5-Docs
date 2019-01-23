.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: () const
    :digest: 9df2535acf090e088971baa4a1bbb23b

Returns a pointer to this buffer's data. You can only read it.

This method is preferred over the const version of :sip:ref:`~PyQt5.QtMultimedia.QAudioBuffer.data` to prevent unnecessary copying.

There is also a templatized version of this  function that allows you to retrieve a specific type of read-only pointer to the data. Note that there is no checking done on the format of the audio buffer - this is simply a convenience function.

::

    // With a 16bit sample buffer:
    const quint16 *data = buffer->constData<quint16>();
