.. sip:method-description::
    :status: todo
    :pysig: 1d557afd38e9b10837d8f94f0b85c942
    :realsig: (int)
    :digest: f6726d4f1d458b15ec31d79ad9a1c89b

Returns a pointer to the pixel data at the scanline with index *i*. The first scanline is at index 0.

The scanline data is aligned on a 32-bit boundary.

**Warning:** If you are accessing 32-bpp image data, cast the returned pointer to ``QRgb\*`` (QRgb has a 32-bit size) and use it to read/write the pixel value. You cannot use the ``uchar\*`` pointer directly, because the pixel format depends on the byte order on the underlying platform. Use :sip:ref:`~PyQt5.QtGui.qRed`, :sip:ref:`~PyQt5.QtGui.qGreen`, :sip:ref:`~PyQt5.QtGui.qBlue`, and :sip:ref:`~PyQt5.QtGui.qAlpha` to access the pixels.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImage.bytesPerLine`, :sip:ref:`~PyQt5.QtGui.QImage.bits`, Pixel Manipulation, :sip:ref:`~PyQt5.QtGui.QImage.constScanLine`.
