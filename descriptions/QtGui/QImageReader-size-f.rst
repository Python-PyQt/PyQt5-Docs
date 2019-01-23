.. sip:method-description::
    :status: todo
    :pysig: 271edd5e2bd089c8749a319b3637d3e6
    :realsig: () const
    :digest: 4ee0eca4135a3e6cda4bd58554f73792

Returns the size of the image, without actually reading the image contents.

If the image format does not support this feature, this function returns an invalid size. Qt's built-in image handlers all support this feature, but custom image format plugins are not required to do so.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageIOHandler.ImageOption`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler.option`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler.supportsOption`.
