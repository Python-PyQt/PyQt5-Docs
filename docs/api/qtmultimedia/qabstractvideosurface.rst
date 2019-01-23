:orphan:

.. sip:class:: PyQt5.QtMultimedia.QAbstractVideoSurface
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtMultimedia/QAbstractVideoSurface-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QAbstractVideoSurface.Error
        :description: QtMultimedia/QAbstractVideoSurface-Error-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoSurface.Error.IncorrectFormatError
            :description: QtMultimedia/QAbstractVideoSurface-Error-IncorrectFormatError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoSurface.Error.NoError
            :description: QtMultimedia/QAbstractVideoSurface-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoSurface.Error.ResourceError
            :description: QtMultimedia/QAbstractVideoSurface-Error-ResourceError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoSurface.Error.StoppedError
            :description: QtMultimedia/QAbstractVideoSurface-Error-StoppedError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QAbstractVideoSurface.Error.UnsupportedFormatError
            :description: QtMultimedia/QAbstractVideoSurface-Error-UnsupportedFormatError-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QAbstractVideoSurface-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.error
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.Error`
        :description: QtMultimedia/QAbstractVideoSurface-error-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.isActive
        :returns:
            bool
        :description: QtMultimedia/QAbstractVideoSurface-isActive-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.isFormatSupported
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :returns:
            bool
        :description: QtMultimedia/QAbstractVideoSurface-isFormatSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.nativeResolution
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QAbstractVideoSurface-nativeResolution-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.nearestFormat
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :description: QtMultimedia/QAbstractVideoSurface-nearestFormat-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.present
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame`
        :returns:
            bool
        :description: QtMultimedia/QAbstractVideoSurface-present-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.setError
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.Error`
        :description: QtMultimedia/QAbstractVideoSurface-setError-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.setNativeResolution
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QAbstractVideoSurface-setNativeResolution-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.start
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :returns:
            bool
        :description: QtMultimedia/QAbstractVideoSurface-start-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.stop
        :description: QtMultimedia/QAbstractVideoSurface-stop-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.supportedPixelFormats
        :args:
            type: :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType` = :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.NoHandle`
        :returns:
            List[:sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.PixelFormat`]
        :description: QtMultimedia/QAbstractVideoSurface-supportedPixelFormats-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QAbstractVideoSurface.surfaceFormat
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :description: QtMultimedia/QAbstractVideoSurface-surfaceFormat-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAbstractVideoSurface.activeChanged
        :args:
            bool
        :description: QtMultimedia/QAbstractVideoSurface-activeChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAbstractVideoSurface.nativeResolutionChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtMultimedia/QAbstractVideoSurface-nativeResolutionChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAbstractVideoSurface.supportedFormatsChanged
        :description: QtMultimedia/QAbstractVideoSurface-supportedFormatsChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QAbstractVideoSurface.surfaceFormatChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat`
        :description: QtMultimedia/QAbstractVideoSurface-surfaceFormatChanged-s.rst
