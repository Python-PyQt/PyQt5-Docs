.. sip:method-description::
    :status: todo
    :pysig: 5de52009a47b50014b2f1fe69a6a5a3c
    :realsig: (const QImage&)
    :digest: be607bda6c54a4ccdbc90c6f57529fd9

Writes the image *image* to the assigned device or file name. Returns ``true`` on success; otherwise returns ``false``. If the operation fails, you can call :sip:ref:`~PyQt5.QtGui.QImageWriter.error` to find the type of error that occurred, or :sip:ref:`~PyQt5.QtGui.QImageWriter.errorString` to get a human readable description of the error.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageWriter.canWrite`, :sip:ref:`~PyQt5.QtGui.QImageWriter.error`, :sip:ref:`~PyQt5.QtGui.QImageWriter.errorString`.
