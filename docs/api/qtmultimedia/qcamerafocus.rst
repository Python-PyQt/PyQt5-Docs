:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCameraFocus
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtMultimedia/QCameraFocus-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraFocus.FocusMode
        :description: QtMultimedia/QCameraFocus-FocusMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusMode.AutoFocus
            :description: QtMultimedia/QCameraFocus-FocusMode-AutoFocus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusMode.ContinuousFocus
            :description: QtMultimedia/QCameraFocus-FocusMode-ContinuousFocus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusMode.HyperfocalFocus
            :description: QtMultimedia/QCameraFocus-FocusMode-HyperfocalFocus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusMode.InfinityFocus
            :description: QtMultimedia/QCameraFocus-FocusMode-InfinityFocus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusMode.MacroFocus
            :description: QtMultimedia/QCameraFocus-FocusMode-MacroFocus-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusMode.ManualFocus
            :description: QtMultimedia/QCameraFocus-FocusMode-ManualFocus-v.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraFocus.FocusPointMode
        :description: QtMultimedia/QCameraFocus-FocusPointMode-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusPointMode.FocusPointAuto
            :description: QtMultimedia/QCameraFocus-FocusPointMode-FocusPointAuto-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusPointMode.FocusPointCenter
            :description: QtMultimedia/QCameraFocus-FocusPointMode-FocusPointCenter-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusPointMode.FocusPointCustom
            :description: QtMultimedia/QCameraFocus-FocusPointMode-FocusPointCustom-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFocus.FocusPointMode.FocusPointFaceDetection
            :description: QtMultimedia/QCameraFocus-FocusPointMode-FocusPointFaceDetection-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.customFocusPoint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtMultimedia/QCameraFocus-customFocusPoint-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.digitalZoom
        :returns:
            float
        :description: QtMultimedia/QCameraFocus-digitalZoom-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.focusMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.FocusModes`
        :description: QtMultimedia/QCameraFocus-focusMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.focusPointMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.FocusPointMode`
        :description: QtMultimedia/QCameraFocus-focusPointMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.focusZones
        :returns:
            List[:sip:ref:`~PyQt5.QtMultimedia.QCameraFocusZone`]
        :description: QtMultimedia/QCameraFocus-focusZones-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.isAvailable
        :returns:
            bool
        :description: QtMultimedia/QCameraFocus-isAvailable-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.isFocusModeSupported
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.FocusModes`
        :returns:
            bool
        :description: QtMultimedia/QCameraFocus-isFocusModeSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.isFocusPointModeSupported
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.FocusPointMode`
        :returns:
            bool
        :description: QtMultimedia/QCameraFocus-isFocusPointModeSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.maximumDigitalZoom
        :returns:
            float
        :description: QtMultimedia/QCameraFocus-maximumDigitalZoom-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.maximumOpticalZoom
        :returns:
            float
        :description: QtMultimedia/QCameraFocus-maximumOpticalZoom-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.opticalZoom
        :returns:
            float
        :description: QtMultimedia/QCameraFocus-opticalZoom-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.setCustomFocusPoint
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtMultimedia/QCameraFocus-setCustomFocusPoint-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.setFocusMode
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.FocusModes`
        :description: QtMultimedia/QCameraFocus-setFocusMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.setFocusPointMode
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFocus.FocusPointMode`
        :description: QtMultimedia/QCameraFocus-setFocusPointMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFocus.zoomTo
        :args:
            float
            float
        :description: QtMultimedia/QCameraFocus-zoomTo-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraFocus.digitalZoomChanged
        :args:
            float
        :description: QtMultimedia/QCameraFocus-digitalZoomChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraFocus.focusZonesChanged
        :description: QtMultimedia/QCameraFocus-focusZonesChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraFocus.maximumDigitalZoomChanged
        :args:
            float
        :description: QtMultimedia/QCameraFocus-maximumDigitalZoomChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraFocus.maximumOpticalZoomChanged
        :args:
            float
        :description: QtMultimedia/QCameraFocus-maximumOpticalZoomChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraFocus.opticalZoomChanged
        :args:
            float
        :description: QtMultimedia/QCameraFocus-opticalZoomChanged-s.rst
