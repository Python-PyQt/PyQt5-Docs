.. sip:class-description::
    :status: todo
    :brief: Set of image encoder settings
    :digest: 1dc4a1b68573caebb3ce60814ec65445

The :sip:ref:`~PyQt5.QtMultimedia.QImageEncoderSettings` class provides a set of image encoder settings.

A image encoder settings object is used to specify the image encoder settings used by :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture`. Image encoder settings are selected by constructing a :sip:ref:`~PyQt5.QtMultimedia.QImageEncoderSettings` object, setting the desired properties and then passing it to a :sip:ref:`~PyQt5.QtMultimedia.QCameraImageCapture` instance using the QCameraImageCapture::setImageSettings() function.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 141-145

.. seealso:: QImageEncoderControl.
