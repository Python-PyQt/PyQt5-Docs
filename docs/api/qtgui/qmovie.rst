:orphan:

.. sip:class:: PyQt5.QtGui.QMovie
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QMovie-c.rst

    .. sip:enum:: PyQt5.QtGui.QMovie.CacheMode
        :description: QtGui/QMovie-CacheMode-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QMovie.CacheMode.CacheAll
            :description: QtGui/QMovie-CacheMode-CacheAll-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QMovie.CacheMode.CacheNone
            :description: QtGui/QMovie-CacheMode-CacheNone-v.rst

    .. sip:enum:: PyQt5.QtGui.QMovie.MovieState
        :description: QtGui/QMovie-MovieState-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QMovie.MovieState.NotRunning
            :description: QtGui/QMovie-MovieState-NotRunning-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QMovie.MovieState.Paused
            :description: QtGui/QMovie-MovieState-Paused-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QMovie.MovieState.Running
            :description: QtGui/QMovie-MovieState-Running-v.rst

    .. sip:method:: PyQt5.QtGui.QMovie.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QMovie-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
            format: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QMovie-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QMovie.__init__
        :args:
            str
            format: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QMovie-__init__-f-2.rst

    .. sip:method:: PyQt5.QtGui.QMovie.backgroundColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtGui/QMovie-backgroundColor-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.cacheMode
        :returns:
            :sip:ref:`~PyQt5.QtGui.QMovie.CacheMode`
        :description: QtGui/QMovie-cacheMode-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.currentFrameNumber
        :returns:
            int
        :description: QtGui/QMovie-currentFrameNumber-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.currentImage
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtGui/QMovie-currentImage-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.currentPixmap
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtGui/QMovie-currentPixmap-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.device
        :returns:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtGui/QMovie-device-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.fileName
        :returns:
            str
        :description: QtGui/QMovie-fileName-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.format
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtGui/QMovie-format-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.frameCount
        :returns:
            int
        :description: QtGui/QMovie-frameCount-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.frameRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QMovie-frameRect-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.isValid
        :returns:
            bool
        :description: QtGui/QMovie-isValid-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.jumpToFrame
        :args:
            int
        :returns:
            bool
        :description: QtGui/QMovie-jumpToFrame-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.jumpToNextFrame
        :returns:
            bool
        :description: QtGui/QMovie-jumpToNextFrame-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.lastError
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImageReader.ImageReaderError`
        :description: QtGui/QMovie-lastError-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.lastErrorString
        :returns:
            str
        :description: QtGui/QMovie-lastErrorString-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.loopCount
        :returns:
            int
        :description: QtGui/QMovie-loopCount-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.nextFrameDelay
        :returns:
            int
        :description: QtGui/QMovie-nextFrameDelay-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.scaledSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QMovie-scaledSize-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setBackgroundColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtGui/QMovie-setBackgroundColor-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setCacheMode
        :args:
            :sip:ref:`~PyQt5.QtGui.QMovie.CacheMode`
        :description: QtGui/QMovie-setCacheMode-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setDevice
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtGui/QMovie-setDevice-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setFileName
        :args:
            str
        :description: QtGui/QMovie-setFileName-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setFormat
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtGui/QMovie-setFormat-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setPaused
        :args:
            bool
        :description: QtGui/QMovie-setPaused-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setScaledSize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QMovie-setScaledSize-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.setSpeed
        :args:
            int
        :description: QtGui/QMovie-setSpeed-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.speed
        :returns:
            int
        :description: QtGui/QMovie-speed-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.start
        :description: QtGui/QMovie-start-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.state
        :returns:
            :sip:ref:`~PyQt5.QtGui.QMovie.MovieState`
        :description: QtGui/QMovie-state-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.stop
        :description: QtGui/QMovie-stop-f.rst

    .. sip:method:: PyQt5.QtGui.QMovie.supportedFormats
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :static:
        :description: QtGui/QMovie-supportedFormats-f.rst

    .. sip:signal:: PyQt5.QtGui.QMovie.error
        :args:
            :sip:ref:`~PyQt5.QtGui.QImageReader.ImageReaderError`
        :description: QtGui/QMovie-error-s.rst

    .. sip:signal:: PyQt5.QtGui.QMovie.finished
        :description: QtGui/QMovie-finished-s.rst

    .. sip:signal:: PyQt5.QtGui.QMovie.frameChanged
        :args:
            int
        :description: QtGui/QMovie-frameChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QMovie.resized
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QMovie-resized-s.rst

    .. sip:signal:: PyQt5.QtGui.QMovie.started
        :description: QtGui/QMovie-started-s.rst

    .. sip:signal:: PyQt5.QtGui.QMovie.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QMovie.MovieState`
        :description: QtGui/QMovie-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QMovie.updated
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QMovie-updated-s.rst
