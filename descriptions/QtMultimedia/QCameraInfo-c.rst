.. sip:class-description::
    :status: todo
    :brief: General information about camera devices
    :digest: 75e5442284d99f96ff5f3ad48e1479d6

The :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo` class provides general information about camera devices.

:sip:ref:`~PyQt5.QtMultimedia.QCameraInfo` lets you query for camera devices that are currently available on the system.

The static functions :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo.defaultCamera` and :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo.availableCameras` provide you a list of all available cameras.

This example prints the name of all available cameras:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 184-186

A :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo` can be used to construct a :sip:ref:`~PyQt5.QtMultimedia.QCamera`. The following example instantiates a :sip:ref:`~PyQt5.QtMultimedia.QCamera` whose camera device is named 'mycamera':

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 193-197

You can also use :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo` to get general information about a camera device such as description, physical position on the system, or camera sensor orientation.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 204-212

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QCamera`.
