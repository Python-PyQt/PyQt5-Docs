.. sip:method-description::
    :status: todo
    :pysig: 271edd5e2bd089c8749a319b3637d3e6
    :realsig: (const QSize&)
    :digest: 46bd2f18c3f7143718740a5c3914e521

Sets the scaled size of the image to *size*. The scaling is performed after the initial clip rect, but before the scaled clip rect is applied. The algorithm used for scaling depends on the image format. By default (i.e., if the image format does not support scaling), :sip:ref:`~PyQt5.QtGui.QImageReader` will use QImage::scale() with Qt::SmoothScaling.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.scaledSize`, :sip:ref:`~PyQt5.QtGui.QImageReader.setClipRect`, :sip:ref:`~PyQt5.QtGui.QImageReader.setScaledClipRect`.
