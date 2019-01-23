.. sip:method-description::
    :status: todo
    :pysig: 1d557afd38e9b10837d8f94f0b85c942
    :realsig: (int) const
    :digest: 9eadfbdc543acb63d4f309ec75505108

Returns a pointer to the pixel data at the scanline with index *i*. The first scanline is at index 0.

The scanline data is aligned on a 32-bit boundary.

Note that :sip:ref:`~PyQt5.QtGui.QImage` uses `implicit data sharing <https://doc.qt.io/qt-5/implicit-sharing.html>`_, but this function does *not* perform a deep copy of the shared pixel data, because the returned data is const.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImage.scanLine`, :sip:ref:`~PyQt5.QtGui.QImage.constBits`.
