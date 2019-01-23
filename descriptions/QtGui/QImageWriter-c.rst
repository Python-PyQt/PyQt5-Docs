.. sip:class-description::
    :status: todo
    :brief: Format independent interface for writing images to files or other devices
    :digest: 97e6c18df54c4465261cf0405e8730f2

The :sip:ref:`~PyQt5.QtGui.QImageWriter` class provides a format independent interface for writing images to files or other devices.

:sip:ref:`~PyQt5.QtGui.QImageWriter` supports setting format specific options, such as the gamma level, compression level and quality, prior to storing the image. If you do not need such options, you can use QImage::save() or :sip:ref:`~PyQt5.QtGui.QPixmap.save` instead.

To store an image, you start by constructing a :sip:ref:`~PyQt5.QtGui.QImageWriter` object. Pass either a file name or a device pointer, and the image format to :sip:ref:`~PyQt5.QtGui.QImageWriter`'s constructor. You can then set several options, such as the gamma level (by calling :sip:ref:`~PyQt5.QtGui.QImageWriter.setGamma`) and quality (by calling :sip:ref:`~PyQt5.QtGui.QImageWriter.setQuality`). :sip:ref:`~PyQt5.QtGui.QImageWriter.canWrite` returns ``true`` if :sip:ref:`~PyQt5.QtGui.QImageWriter` can write the image (i.e., the image format is supported and the device is open for writing). Call :sip:ref:`~PyQt5.QtGui.QImageWriter.write` to write the image to the device.

If any error occurs when writing the image, :sip:ref:`~PyQt5.QtGui.QImageWriter.write` will return false. You can then call :sip:ref:`~PyQt5.QtGui.QImageWriter.error` to find the type of error that occurred, or :sip:ref:`~PyQt5.QtGui.QImageWriter.errorString` to get a human readable description of what went wrong.

Call :sip:ref:`~PyQt5.QtGui.QImageWriter.supportedImageFormats` for a list of formats that :sip:ref:`~PyQt5.QtGui.QImageWriter` can write. :sip:ref:`~PyQt5.QtGui.QImageWriter` supports all built-in image formats, in addition to any image format plugins that support writing.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler`, QImageIOPlugin.
