.. sip:class-description::
    :status: todo
    :brief: Set of viewfinder settings
    :digest: 93489b24e38576ad1f7f979718ae6475

The :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings` class provides a set of viewfinder settings.

A viewfinder settings object is used to specify the viewfinder settings used by :sip:ref:`~PyQt5.QtMultimedia.QCamera`. Viewfinder settings are selected by constructing a :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings` object, setting the desired properties and then passing it to a :sip:ref:`~PyQt5.QtMultimedia.QCamera` instance using the :sip:ref:`~PyQt5.QtMultimedia.QCamera.setViewfinderSettings` function.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 289-294

Different cameras may have different capabilities. The application should query the camera capabilities before setting parameters. For example, the application should call :sip:ref:`~PyQt5.QtMultimedia.QCamera.supportedViewfinderResolutions` before calling :sip:ref:`~PyQt5.QtMultimedia.QCameraViewfinderSettings.setResolution`.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QCamera`.
