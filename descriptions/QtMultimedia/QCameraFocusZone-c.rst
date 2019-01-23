.. sip:class-description::
    :status: todo
    :brief: Information on zones used for autofocusing a camera
    :digest: f6dcd4d68f74b6d2789e0395b463fce3

The :sip:ref:`~PyQt5.QtMultimedia.QCameraFocusZone` class provides information on zones used for autofocusing a camera.

For cameras that support autofocusing, in order for a camera to autofocus on part of a sensor frame, it considers different zones within the frame. Which zones to use, and where the zones are located vary between different cameras.

This class exposes what zones are used by a particular camera, and a list of the zones can be retrieved by a :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus` instance.

You can use this information to present visual feedback - for example, drawing rectangles around areas of the camera frame that are in focus, or changing the color of a zone as it comes into focus.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 273-282

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus`.
