.. sip:method-description::
    :status: todo
    :pysig: 69247b1eee4352b7ad751dbec74b85b6
    :realsig: (quint32,QRawFont::AntialiasingType,const QTransform&) const
    :digest: 8e01fbc27fd41f1a8405f1805fe6ab47

This function returns a rasterized image of the glyph at the given *glyphIndex* in the underlying font, using the *transform* specified. If the :sip:ref:`~PyQt5.QtGui.QRawFont` is not valid, this function will return an invalid :sip:ref:`~PyQt5.QtGui.QImage`.

If the font is a color font, then the resulting image will contain the rendered glyph at the current pixel size. In this case, the *antialiasingType* will be ignored.

Otherwise, if *antialiasingType* is set to :sip:ref:`~PyQt5.QtGui.QRawFont.AntialiasingType.SubPixelAntialiasing`, then the resulting image will be in :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_RGB32` and the RGB values of each pixel will represent the subpixel opacities of the pixel in the rasterization of the glyph. Otherwise, the image will be in the format of :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_Indexed8` and each pixel will contain the opacity of the pixel in the rasterization.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QRawFont.pathForGlyph`, :sip:ref:`~PyQt5.QtGui.QPainter.drawGlyphRun`.
