:orphan:

.. sip:class:: PyQt5.QtGui.QImageWriter
    :description: QtGui/QImageWriter-c.rst

    .. sip:enum:: PyQt5.QtGui.QImageWriter.ImageWriterError
        :description: QtGui/QImageWriter-ImageWriterError-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QImageWriter.ImageWriterError.DeviceError
            :description: QtGui/QImageWriter-ImageWriterError-DeviceError-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QImageWriter.ImageWriterError.InvalidImageError
            :description: QtGui/QImageWriter-ImageWriterError-InvalidImageError-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QImageWriter.ImageWriterError.UnknownError
            :description: QtGui/QImageWriter-ImageWriterError-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QImageWriter.ImageWriterError.UnsupportedFormatError
            :description: QtGui/QImageWriter-ImageWriterError-UnsupportedFormatError-v.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.__init__
        :description: QtGui/QImageWriter-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtGui/QImageWriter-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.__init__
        :args:
            str
            format: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
        :description: QtGui/QImageWriter-__init__-f-2.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.canWrite
        :returns:
            bool
        :description: QtGui/QImageWriter-canWrite-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.compression
        :returns:
            int
        :description: QtGui/QImageWriter-compression-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.device
        :returns:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtGui/QImageWriter-device-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.error
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImageWriter.ImageWriterError`
        :description: QtGui/QImageWriter-error-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.errorString
        :returns:
            str
        :description: QtGui/QImageWriter-errorString-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.fileName
        :returns:
            str
        :description: QtGui/QImageWriter-fileName-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.format
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtGui/QImageWriter-format-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.gamma
        :returns:
            float
        :description: QtGui/QImageWriter-gamma-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.imageFormatsForMimeType
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :static:
        :description: QtGui/QImageWriter-imageFormatsForMimeType-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.optimizedWrite
        :returns:
            bool
        :description: QtGui/QImageWriter-optimizedWrite-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.progressiveScanWrite
        :returns:
            bool
        :description: QtGui/QImageWriter-progressiveScanWrite-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.quality
        :returns:
            int
        :description: QtGui/QImageWriter-quality-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setCompression
        :args:
            int
        :description: QtGui/QImageWriter-setCompression-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setDevice
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtGui/QImageWriter-setDevice-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setFileName
        :args:
            str
        :description: QtGui/QImageWriter-setFileName-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setFormat
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtGui/QImageWriter-setFormat-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setGamma
        :args:
            float
        :description: QtGui/QImageWriter-setGamma-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setOptimizedWrite
        :args:
            bool
        :description: QtGui/QImageWriter-setOptimizedWrite-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setProgressiveScanWrite
        :args:
            bool
        :description: QtGui/QImageWriter-setProgressiveScanWrite-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setQuality
        :args:
            int
        :description: QtGui/QImageWriter-setQuality-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setSubType
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtGui/QImageWriter-setSubType-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setText
        :args:
            str
            str
        :description: QtGui/QImageWriter-setText-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.setTransformation
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QImageIOHandler.Transformations`, :sip:ref:`~PyQt5.QtGui.QImageIOHandler.Transformation`]
        :description: QtGui/QImageWriter-setTransformation-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.subType
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtGui/QImageWriter-subType-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.supportedImageFormats
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :static:
        :description: QtGui/QImageWriter-supportedImageFormats-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.supportedMimeTypes
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :static:
        :description: QtGui/QImageWriter-supportedMimeTypes-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.supportedSubTypes
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtGui/QImageWriter-supportedSubTypes-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.supportsOption
        :args:
            :sip:ref:`~PyQt5.QtGui.QImageIOHandler.ImageOption`
        :returns:
            bool
        :description: QtGui/QImageWriter-supportsOption-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.transformation
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImageIOHandler.Transformations`
        :description: QtGui/QImageWriter-transformation-f.rst

    .. sip:method:: PyQt5.QtGui.QImageWriter.write
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :returns:
            bool
        :description: QtGui/QImageWriter-write-f.rst
