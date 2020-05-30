:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCameraControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QCameraControl-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraControl.PropertyChangeType
        :description: QtMultimedia/QCameraControl-PropertyChangeType-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraControl.PropertyChangeType.CaptureMode
            :description: QtMultimedia/QCameraControl-PropertyChangeType-CaptureMode-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraControl.PropertyChangeType.ImageEncodingSettings
            :description: QtMultimedia/QCameraControl-PropertyChangeType-ImageEncodingSettings-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraControl.PropertyChangeType.VideoEncodingSettings
            :description: QtMultimedia/QCameraControl-PropertyChangeType-VideoEncodingSettings-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraControl.PropertyChangeType.Viewfinder
            :description: QtMultimedia/QCameraControl-PropertyChangeType-Viewfinder-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraControl.PropertyChangeType.ViewfinderSettings
            :description: QtMultimedia/QCameraControl-PropertyChangeType-ViewfinderSettings-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCameraControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.canChangeProperty
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraControl.PropertyChangeType`
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Status`
        :returns:
            bool
        :description: QtMultimedia/QCameraControl-canChangeProperty-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.captureMode
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`
        :description: QtMultimedia/QCameraControl-captureMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.isCaptureModeSupported
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureMode`]
        :returns:
            bool
        :description: QtMultimedia/QCameraControl-isCaptureModeSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.setCaptureMode
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureMode`]
        :description: QtMultimedia/QCameraControl-setCaptureMode-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.setState
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.State`
        :description: QtMultimedia/QCameraControl-setState-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.state
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.State`
        :description: QtMultimedia/QCameraControl-state-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraControl.status
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Status`
        :description: QtMultimedia/QCameraControl-status-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraControl.captureModeChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureModes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.CaptureMode`]
        :description: QtMultimedia/QCameraControl-captureModeChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraControl.error
        :args:
            int
            str
        :description: QtMultimedia/QCameraControl-error-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraControl.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.State`
        :description: QtMultimedia/QCameraControl-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraControl.statusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.Status`
        :description: QtMultimedia/QCameraControl-statusChanged-s.rst
