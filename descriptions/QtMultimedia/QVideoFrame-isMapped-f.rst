.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 19cc9592a6ddfab87ab149dda381f10b

Identifies if a video frame's contents are currently mapped to system memory.

This is a convenience function which checks that the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode` of the frame is not equal to :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode.NotMapped`.

Returns true if the contents of the video frame are mapped to system memory, and false otherwise.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.mapMode`, :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode`.
