.. sip:method-description::
    :status: todo
    :pysig: cc033c2a8afe49ee8034a7055eb3a6a3
    :realsig: (const QRectF&,const QSize&,QOpenGLTextureBlitter::Origin)
    :digest: d34652dc7f688910a59ac574081a7282

Calculates a 3x3 matrix suitable as the input to :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter.blit`. This is used when only a part of the texture is to be used in the blit.

*subTexture* is the desired source rectangle in pixels, *textureSize* is the full width and height of the texture data. *origin* specifies the orientation of the image data when it comes to the Y axis.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter.blit`, :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter.Origin.Origin`.
