:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCameraExposureControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QCameraExposureControl-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter
        :description: QtMultimedia/QCameraExposureControl-ExposureParameter-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.Aperture
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-Aperture-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.ExposureCompensation
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-ExposureCompensation-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.ExposureMode
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-ExposureMode-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.ExtendedExposureParameter
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-ExtendedExposureParameter-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.FlashCompensation
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-FlashCompensation-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.FlashPower
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-FlashPower-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.ISO
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-ISO-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.MeteringMode
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-MeteringMode-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.ShutterSpeed
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-ShutterSpeed-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.SpotMeteringPoint
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-SpotMeteringPoint-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter.TorchPower
            :description: QtMultimedia/QCameraExposureControl-ExposureParameter-TorchPower-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraExposureControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCameraExposureControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraExposureControl.actualValue
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter`
        :returns:
            Any
        :description: QtMultimedia/QCameraExposureControl-actualValue-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraExposureControl.isParameterSupported
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter`
        :returns:
            bool
        :description: QtMultimedia/QCameraExposureControl-isParameterSupported-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraExposureControl.requestedValue
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter`
        :returns:
            Any
        :description: QtMultimedia/QCameraExposureControl-requestedValue-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraExposureControl.setValue
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter`
            Any
        :returns:
            bool
        :description: QtMultimedia/QCameraExposureControl-setValue-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraExposureControl.supportedParameterRange
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCameraExposureControl.ExposureParameter`
        :returns:
            List[Any]
            bool
        :description: QtMultimedia/QCameraExposureControl-supportedParameterRange-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraExposureControl.actualValueChanged
        :args:
            int
        :description: QtMultimedia/QCameraExposureControl-actualValueChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraExposureControl.parameterRangeChanged
        :args:
            int
        :description: QtMultimedia/QCameraExposureControl-parameterRangeChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraExposureControl.requestedValueChanged
        :args:
            int
        :description: QtMultimedia/QCameraExposureControl-requestedValueChanged-s.rst
