.. sip:method-description::
    :status: todo
    :pysig: 450ebbb91b1af08ea33413e61783410f
    :realsig: () const
    :digest: b1ea2f42a0e33d56410369693557c256

Converts the pixmap to a :sip:ref:`~PyQt5.QtGui.QImage`. Returns a null image if the conversion fails.

If the pixmap has 1-bit depth, the returned image will also be 1 bit deep. Images with more bits will be returned in a format closely represents the underlying system. Usually this will be :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_ARGB32_Premultiplied` for pixmaps with an alpha and :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_RGB32` or :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_RGB16` for pixmaps without alpha.

Note that for the moment, alpha masks on monochrome images are ignored.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPixmap.fromImage`, Image Formats.
