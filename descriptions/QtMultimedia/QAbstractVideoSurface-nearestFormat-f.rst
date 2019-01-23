.. sip:method-description::
    :status: todo
    :pysig: e1820aeec99afff74df1381ad55b8564
    :realsig: (const QVideoSurfaceFormat&) const
    :digest: fc551c3034e6fa1d8a065ae8b2a1d344

Returns a supported video surface format that is similar to *format*.

A similar surface format is one that has the same :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.pixelFormat` and :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.handleType` but may differ in some of the other properties. For example, if there are restrictions on the :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.frameSize` a video surface can accept it may suggest a format with a larger frame size and a :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.viewport` the size of the original frame size.

If the format is already supported it will be returned unchanged, or if there is no similar supported format an invalid format will be returned.
