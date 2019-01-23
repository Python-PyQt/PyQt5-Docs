.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 8625ed1494e6f6c8404efe70e2b798ac

Returns the number of bytes in a scan line.

**Note:** For planar formats this is the bytes per line of the first plane only. The bytes per line of subsequent planes should be calculated as per the frame :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`.

This value is only valid while the frame data is :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.map`.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.bits`, :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.map`, :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.mappedBytes`.
