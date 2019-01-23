.. sip:method-description::
    :status: todo
    :pysig: 1449941ef4f7387942860955e4dc2ac0
    :realsig: (const QImage&)
    :digest: 863a503b239ed08513ada34efa8c4d4a

Converts the image *img* into the unnamed format expected by OpenGL functions such as glTexImage2D(). The returned image is not usable as a :sip:ref:`~PyQt5.QtGui.QImage`, but QImage::width(), QImage::height() and QImage::bits() may be used with OpenGL. The GL format used is ``GL_RGBA``.
