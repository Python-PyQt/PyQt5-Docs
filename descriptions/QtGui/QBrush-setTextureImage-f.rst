.. sip:method-description::
    :status: todo
    :pysig: 450ebbb91b1af08ea33413e61783410f
    :realsig: (const QImage&)
    :digest: 111e8fb08a0b747dcc813458d0000dae

Sets the brush image to *image*. The style is set to :sip:ref:`~PyQt5.QtCore.Qt.BrushStyle.TexturePattern`.

Note the current brush color will *not* have any affect on monochrome images, as opposed to calling :sip:ref:`~PyQt5.QtGui.QBrush.setTexture` with a :sip:ref:`~PyQt5.QtGui.QBitmap`. If you want to change the color of monochrome image brushes, either convert the image to :sip:ref:`~PyQt5.QtGui.QBitmap` with ``QBitmap::fromImage()`` and set the resulting :sip:ref:`~PyQt5.QtGui.QBitmap` as a texture, or change the entries in the color table for the image.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QBrush.textureImage`, :sip:ref:`~PyQt5.QtGui.QBrush.setTexture`.
