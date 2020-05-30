:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCameraImageCaptureControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QCameraImageCaptureControl-c.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCaptureControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCameraImageCaptureControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCaptureControl.cancelCapture
        :description: QtMultimedia/QCameraImageCaptureControl-cancelCapture-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCaptureControl.capture
        :args:
            str
        :returns:
            int
        :description: QtMultimedia/QCameraImageCaptureControl-capture-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCaptureControl.driveMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.DriveMode`
        :description: QtMultimedia/QCameraImageCaptureControl-driveMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCaptureControl.isReadyForCapture
        :returns:
            bool
        :description: QtMultimedia/QCameraImageCaptureControl-isReadyForCapture-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraImageCaptureControl.setDriveMode
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.DriveMode`
        :description: QtMultimedia/QCameraImageCaptureControl-setDriveMode-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCaptureControl.error
        :args:
            int
            int
            str
        :description: QtMultimedia/QCameraImageCaptureControl-error-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCaptureControl.imageAvailable
        :args:
            int
            :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame`
        :description: QtMultimedia/QCameraImageCaptureControl-imageAvailable-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCaptureControl.imageCaptured
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtMultimedia/QCameraImageCaptureControl-imageCaptured-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCaptureControl.imageExposed
        :args:
            int
        :description: QtMultimedia/QCameraImageCaptureControl-imageExposed-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCaptureControl.imageMetadataAvailable
        :args:
            int
            str
            Any
        :description: QtMultimedia/QCameraImageCaptureControl-imageMetadataAvailable-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCaptureControl.imageSaved
        :args:
            int
            str
        :description: QtMultimedia/QCameraImageCaptureControl-imageSaved-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraImageCaptureControl.readyForCaptureChanged
        :args:
            bool
        :description: QtMultimedia/QCameraImageCaptureControl-readyForCaptureChanged-s.rst
