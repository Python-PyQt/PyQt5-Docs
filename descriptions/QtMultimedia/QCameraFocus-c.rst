.. sip:class-description::
    :status: todo
    :brief: Interface for focus and zoom related camera settings
    :digest: 8014d1ff6379b88be729d0389772a5cd

The :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus` class provides an interface for focus and zoom related camera settings.

On hardware that supports it, this class lets you adjust the focus or zoom (both optical and digital). This also includes things like "Macro" mode for close up work (e.g. reading barcodes, or recognising letters), or "touch to focus" - indicating an interesting area of the viewfinder for the hardware to attempt to focus on.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 263-265

Zooming can be accomplished in a number of ways - usually the more expensive but higher quality approach is an optical zoom, which allows using the full extent of the camera sensor to gather image pixels. In addition it is possible to digitally zoom, which will generally just enlarge part of the sensor frame and throw away other parts. If the camera hardware supports optical zoom this should generally always be used first. The :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.maximumOpticalZoom` method allows this to be checked. The :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.zoomTo` method allows changing both optical and digital zoom at once.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 269-269

.. _qcamerafocus-some-notes-on-autofocus:

Some notes on autofocus
.......................

Some hardware supports a movable focus lens assembly, and typically this hardware also supports automatically focusing via some heuristic. You can influence this via the :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.FocusPointMode.FocusPointMode` setting - typically the center of the frame is brought into focus, but some hardware also supports focusing on any faces detected in the frame, or on a specific point (usually provided by a user in a "touch to focus" scenario).

This class (in combination with :sip:ref:`~PyQt5.QtMultimedia.QCameraFocusZone`) can expose information on what parts of the camera sensor image are in focus or are being used for autofocusing via the :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.focusZones` property:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-camera.py
    :lines: 273-282

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QCameraFocusZone`.
