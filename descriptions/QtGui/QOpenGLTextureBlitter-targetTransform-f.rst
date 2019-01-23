.. sip:method-description::
    :status: todo
    :pysig: 55c11be84f16ba7ec8e36a285dc3b91d
    :realsig: (const QRectF&,const QRect&)
    :digest: 48c99d4ee0295d2ce0b0c03a280ea379

Calculates a target transform suitable for :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter.blit`.

*target* is the target rectangle in pixels. *viewport* describes the source dimensions and will in most cases be set to (0, 0, image width, image height).

For unscaled output the size of *target* and *viewport* should match.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter.blit`.
