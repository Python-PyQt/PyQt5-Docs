:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCameraFeedbackControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QCameraFeedbackControl-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType
        :description: QtMultimedia/QCameraFeedbackControl-EventType-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.AutoFocusFailed
            :description: QtMultimedia/QCameraFeedbackControl-EventType-AutoFocusFailed-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.AutoFocusInProgress
            :description: QtMultimedia/QCameraFeedbackControl-EventType-AutoFocusInProgress-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.AutoFocusLocked
            :description: QtMultimedia/QCameraFeedbackControl-EventType-AutoFocusLocked-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.ImageCaptured
            :description: QtMultimedia/QCameraFeedbackControl-EventType-ImageCaptured-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.ImageError
            :description: QtMultimedia/QCameraFeedbackControl-EventType-ImageError-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.ImageSaved
            :description: QtMultimedia/QCameraFeedbackControl-EventType-ImageSaved-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.RecordingInProgress
            :description: QtMultimedia/QCameraFeedbackControl-EventType-RecordingInProgress-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.RecordingStarted
            :description: QtMultimedia/QCameraFeedbackControl-EventType-RecordingStarted-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.RecordingStopped
            :description: QtMultimedia/QCameraFeedbackControl-EventType-RecordingStopped-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.ViewfinderStarted
            :description: QtMultimedia/QCameraFeedbackControl-EventType-ViewfinderStarted-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraFeedbackControl.EventType.ViewfinderStopped
            :description: QtMultimedia/QCameraFeedbackControl-EventType-ViewfinderStopped-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFeedbackControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCameraFeedbackControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFeedbackControl.isEventFeedbackEnabled
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFeedbackControl.EventType`
        :returns:
            bool
        :description: QtMultimedia/QCameraFeedbackControl-isEventFeedbackEnabled-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFeedbackControl.isEventFeedbackLocked
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFeedbackControl.EventType`
        :returns:
            bool
        :description: QtMultimedia/QCameraFeedbackControl-isEventFeedbackLocked-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFeedbackControl.resetEventFeedback
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFeedbackControl.EventType`
        :description: QtMultimedia/QCameraFeedbackControl-resetEventFeedback-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFeedbackControl.setEventFeedbackEnabled
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFeedbackControl.EventType`
            bool
        :returns:
            bool
        :description: QtMultimedia/QCameraFeedbackControl-setEventFeedbackEnabled-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraFeedbackControl.setEventFeedbackSound
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraFeedbackControl.EventType`
            str
        :returns:
            bool
        :description: QtMultimedia/QCameraFeedbackControl-setEventFeedbackSound-f.rst
