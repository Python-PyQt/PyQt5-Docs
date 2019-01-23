.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: ()
    :digest: 6aa3e3e69d70f8d30cab9384e73587a8

Returns a pointer to the start of the frame data buffer.

This value is only valid while the frame data is :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.map`.

Changes made to data accessed via this pointer (when mapped with write access) are only guaranteed to have been persisted when :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.unmap` is called and when the buffer has been mapped for writing.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.map`, :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.mappedBytes`, :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.bytesPerLine`.
