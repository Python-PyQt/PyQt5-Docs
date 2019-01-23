.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 5db3fd9c882405407981366fe18446c2

Identifies if the mapped contents of a video frame were read from the frame when it was mapped.

This is a convenience function which checks if the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode` contains the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode.WriteOnly` flag.

Returns true if the contents of the mapped memory were read from the video frame, and false otherwise.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.mapMode`, :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode`.
