.. sip:class-description::
    :status: todo
    :brief: Interface for image processing related camera settings
    :digest: 6eb009df822ecb117908ec6a334b220f

The :sip:ref:`~PyQt5.QtMultimedia.QCameraImageProcessing` class provides an interface for image processing related camera settings.

After capturing the data for a camera frame, the camera hardware and software performs various image processing tasks to produce a final image. This includes compensating for ambient light color, reducing noise, as well as making some other adjustments to the image.

You can retrieve this class from an instance of a :sip:ref:`~PyQt5.QtMultimedia.QCamera` object.

For example, you can set the white balance (or color temperature) used for processing images:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 247-252

Or adjust the amount of denoising performed:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 256-256

In some cases changing these settings may result in a longer delay before an image is ready.

For more information on image processing of camera frames, see `Camera Image Processing <https://doc.qt.io/qt-5/cameraoverview.html#camera-image-processing>`_.

.. seealso:: QCameraImageProcessingControl.
