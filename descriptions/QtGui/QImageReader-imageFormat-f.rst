.. sip:method-description::
    :status: todo
    :pysig: 683336077a81e83d0a52a2d7e3174c54
    :realsig: () const
    :digest: 4f7cb957f1fb47cb8a550e3f282726ca

Returns the format of the image, without actually reading the image contents. The format describes the image format :sip:ref:`~PyQt5.QtGui.QImageReader.read` returns, not the format of the actual image.

If the image format does not support this feature, this function returns an invalid format.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageIOHandler.ImageOption`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler.option`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler.supportsOption`.
