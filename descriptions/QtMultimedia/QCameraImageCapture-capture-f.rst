.. sip:method-description::
    :status: todo
    :pysig: bb225e240991ddd6e538715a87871b5e
    :realsig: (const QString&)
    :digest: 3d7819d3efda2be3e2e7808fb17a17d7

Capture the image and save it to *file*. This operation is asynchronous in majority of cases, followed by signals :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageExposed`, :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageCaptured`, :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageSaved` or :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.error`.

If an empty *file* is passed, the camera backend choses the default location and naming scheme for photos on the system, if only file name without full path is specified, the image will be saved to the default directory, with a full path reported with :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageCaptured` and :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageSaved` signals.

:sip:ref:`~PyQt5.QtMultimedia.QCamera` saves all the capture parameters like exposure settings or image processing parameters, so changes to camera parameters after  is called do not affect previous capture requests.

returns the capture Id parameter, used with :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageExposed`, :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageCaptured` and :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.imageSaved` signals.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture.isReadyForCapture`.
