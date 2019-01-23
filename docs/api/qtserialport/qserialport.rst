:orphan:

.. sip:class:: PyQt5.QtSerialPort.QSerialPort
    :inherits: :sip:ref:`~PyQt5.QtCore.QIODevice`
    :description: QtSerialPort/QSerialPort-c.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.BaudRate
        :description: QtSerialPort/QSerialPort-BaudRate-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud115200
            :description: QtSerialPort/QSerialPort-BaudRate-Baud115200-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud1200
            :description: QtSerialPort/QSerialPort-BaudRate-Baud1200-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud19200
            :description: QtSerialPort/QSerialPort-BaudRate-Baud19200-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud2400
            :description: QtSerialPort/QSerialPort-BaudRate-Baud2400-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud38400
            :description: QtSerialPort/QSerialPort-BaudRate-Baud38400-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud4800
            :description: QtSerialPort/QSerialPort-BaudRate-Baud4800-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud57600
            :description: QtSerialPort/QSerialPort-BaudRate-Baud57600-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.Baud9600
            :description: QtSerialPort/QSerialPort-BaudRate-Baud9600-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.BaudRate.UnknownBaud
            :description: QtSerialPort/QSerialPort-BaudRate-UnknownBaud-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.DataBits
        :description: QtSerialPort/QSerialPort-DataBits-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataBits.Data5
            :description: QtSerialPort/QSerialPort-DataBits-Data5-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataBits.Data6
            :description: QtSerialPort/QSerialPort-DataBits-Data6-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataBits.Data7
            :description: QtSerialPort/QSerialPort-DataBits-Data7-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataBits.Data8
            :description: QtSerialPort/QSerialPort-DataBits-Data8-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataBits.UnknownDataBits
            :description: QtSerialPort/QSerialPort-DataBits-UnknownDataBits-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy
        :description: QtSerialPort/QSerialPort-DataErrorPolicy-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy.IgnorePolicy
            :description: QtSerialPort/QSerialPort-DataErrorPolicy-IgnorePolicy-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy.PassZeroPolicy
            :description: QtSerialPort/QSerialPort-DataErrorPolicy-PassZeroPolicy-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy.SkipPolicy
            :description: QtSerialPort/QSerialPort-DataErrorPolicy-SkipPolicy-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy.StopReceivingPolicy
            :description: QtSerialPort/QSerialPort-DataErrorPolicy-StopReceivingPolicy-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy.UnknownPolicy
            :description: QtSerialPort/QSerialPort-DataErrorPolicy-UnknownPolicy-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.Direction
        :description: QtSerialPort/QSerialPort-Direction-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Direction.AllDirections
            :description: QtSerialPort/QSerialPort-Direction-AllDirections-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Direction.Input
            :description: QtSerialPort/QSerialPort-Direction-Input-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Direction.Output
            :description: QtSerialPort/QSerialPort-Direction-Output-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.FlowControl
        :description: QtSerialPort/QSerialPort-FlowControl-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.FlowControl.HardwareControl
            :description: QtSerialPort/QSerialPort-FlowControl-HardwareControl-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.FlowControl.NoFlowControl
            :description: QtSerialPort/QSerialPort-FlowControl-NoFlowControl-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.FlowControl.SoftwareControl
            :description: QtSerialPort/QSerialPort-FlowControl-SoftwareControl-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.FlowControl.UnknownFlowControl
            :description: QtSerialPort/QSerialPort-FlowControl-UnknownFlowControl-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.Parity
        :description: QtSerialPort/QSerialPort-Parity-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Parity.EvenParity
            :description: QtSerialPort/QSerialPort-Parity-EvenParity-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Parity.MarkParity
            :description: QtSerialPort/QSerialPort-Parity-MarkParity-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Parity.NoParity
            :description: QtSerialPort/QSerialPort-Parity-NoParity-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Parity.OddParity
            :description: QtSerialPort/QSerialPort-Parity-OddParity-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Parity.SpaceParity
            :description: QtSerialPort/QSerialPort-Parity-SpaceParity-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.Parity.UnknownParity
            :description: QtSerialPort/QSerialPort-Parity-UnknownParity-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal
        :description: QtSerialPort/QSerialPort-PinoutSignal-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.ClearToSendSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-ClearToSendSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.DataCarrierDetectSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-DataCarrierDetectSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.DataSetReadySignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-DataSetReadySignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.DataTerminalReadySignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-DataTerminalReadySignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.NoSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-NoSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.ReceivedDataSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-ReceivedDataSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.RequestToSendSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-RequestToSendSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.RingIndicatorSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-RingIndicatorSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.SecondaryReceivedDataSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-SecondaryReceivedDataSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.SecondaryTransmittedDataSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-SecondaryTransmittedDataSignal-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.PinoutSignal.TransmittedDataSignal
            :description: QtSerialPort/QSerialPort-PinoutSignal-TransmittedDataSignal-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.SerialPortError
        :description: QtSerialPort/QSerialPort-SerialPortError-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.BreakConditionError
            :description: QtSerialPort/QSerialPort-SerialPortError-BreakConditionError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.DeviceNotFoundError
            :description: QtSerialPort/QSerialPort-SerialPortError-DeviceNotFoundError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.FramingError
            :description: QtSerialPort/QSerialPort-SerialPortError-FramingError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.NoError
            :description: QtSerialPort/QSerialPort-SerialPortError-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.NotOpenError
            :description: QtSerialPort/QSerialPort-SerialPortError-NotOpenError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.OpenError
            :description: QtSerialPort/QSerialPort-SerialPortError-OpenError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.ParityError
            :description: QtSerialPort/QSerialPort-SerialPortError-ParityError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.PermissionError
            :description: QtSerialPort/QSerialPort-SerialPortError-PermissionError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.ReadError
            :description: QtSerialPort/QSerialPort-SerialPortError-ReadError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.ResourceError
            :description: QtSerialPort/QSerialPort-SerialPortError-ResourceError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.TimeoutError
            :description: QtSerialPort/QSerialPort-SerialPortError-TimeoutError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.UnknownError
            :description: QtSerialPort/QSerialPort-SerialPortError-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.UnsupportedOperationError
            :description: QtSerialPort/QSerialPort-SerialPortError-UnsupportedOperationError-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.SerialPortError.WriteError
            :description: QtSerialPort/QSerialPort-SerialPortError-WriteError-v.rst

    .. sip:enum:: PyQt5.QtSerialPort.QSerialPort.StopBits
        :description: QtSerialPort/QSerialPort-StopBits-e.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.StopBits.OneAndHalfStop
            :description: QtSerialPort/QSerialPort-StopBits-OneAndHalfStop-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.StopBits.OneStop
            :description: QtSerialPort/QSerialPort-StopBits-OneStop-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.StopBits.TwoStop
            :description: QtSerialPort/QSerialPort-StopBits-TwoStop-v.rst

        .. sip:enum-member:: PyQt5.QtSerialPort.QSerialPort.StopBits.UnknownStopBits
            :description: QtSerialPort/QSerialPort-StopBits-UnknownStopBits-v.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtSerialPort/QSerialPort-__init__-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.__init__
        :args:
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtSerialPort/QSerialPort-__init__-f-1.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.__init__
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPortInfo`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtSerialPort/QSerialPort-__init__-f-2.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.atEnd
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-atEnd-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.baudRate
        :args:
            dir: Union[:sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Directions`, :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Direction`] = :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Direction.AllDirections`
        :returns:
            int
        :description: QtSerialPort/QSerialPort-baudRate-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.bytesAvailable
        :returns:
            int
        :description: QtSerialPort/QSerialPort-bytesAvailable-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.bytesToWrite
        :returns:
            int
        :description: QtSerialPort/QSerialPort-bytesToWrite-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.canReadLine
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-canReadLine-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.clear
        :args:
            dir: Union[:sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Directions`, :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Direction`] = :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Direction.AllDirections`
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-clear-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.clearError
        :description: QtSerialPort/QSerialPort-clearError-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.close
        :description: QtSerialPort/QSerialPort-close-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.dataBits
        :returns:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.DataBits`
        :description: QtSerialPort/QSerialPort-dataBits-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.dataErrorPolicy
        :returns:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy`
        :description: QtSerialPort/QSerialPort-dataErrorPolicy-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.error
        :returns:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.SerialPortError`
        :description: QtSerialPort/QSerialPort-error-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.flowControl
        :returns:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.FlowControl`
        :description: QtSerialPort/QSerialPort-flowControl-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.flush
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-flush-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.handle
        :returns:
            sip.voidptr
        :description: QtSerialPort/QSerialPort-handle-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.handle
        :returns:
            int
        :description: QtSerialPort/QSerialPort-handle-f-1.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.isBreakEnabled
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-isBreakEnabled-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.isDataTerminalReady
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-isDataTerminalReady-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.isRequestToSend
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-isRequestToSend-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.isSequential
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-isSequential-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.open
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`]
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-open-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.parity
        :returns:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Parity`
        :description: QtSerialPort/QSerialPort-parity-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.pinoutSignals
        :returns:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.PinoutSignals`
        :description: QtSerialPort/QSerialPort-pinoutSignals-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.portName
        :returns:
            str
        :description: QtSerialPort/QSerialPort-portName-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.readBufferSize
        :returns:
            int
        :description: QtSerialPort/QSerialPort-readBufferSize-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.readData
        :args:
            int
        :returns:
            bytes
        :description: QtSerialPort/QSerialPort-readData-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.readLineData
        :args:
            int
        :returns:
            bytes
        :description: QtSerialPort/QSerialPort-readLineData-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.sendBreak
        :args:
            duration: int = 0
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-sendBreak-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setBaudRate
        :args:
            int
            dir: Union[:sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Directions`, :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Direction`] = :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Direction.AllDirections`
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setBaudRate-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setBreakEnabled
        :args:
            enabled: bool = True
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setBreakEnabled-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setDataBits
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.DataBits`
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setDataBits-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setDataErrorPolicy
        :args:
            policy: :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy` = :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy.IgnorePolicy`
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setDataErrorPolicy-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setDataTerminalReady
        :args:
            bool
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setDataTerminalReady-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setFlowControl
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.FlowControl`
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setFlowControl-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setParity
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Parity`
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setParity-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setPort
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPortInfo`
        :description: QtSerialPort/QSerialPort-setPort-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setPortName
        :args:
            str
        :description: QtSerialPort/QSerialPort-setPortName-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setReadBufferSize
        :args:
            int
        :description: QtSerialPort/QSerialPort-setReadBufferSize-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setRequestToSend
        :args:
            bool
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setRequestToSend-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setSettingsRestoredOnClose
        :args:
            bool
        :description: QtSerialPort/QSerialPort-setSettingsRestoredOnClose-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.setStopBits
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.StopBits`
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-setStopBits-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.settingsRestoredOnClose
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-settingsRestoredOnClose-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.stopBits
        :returns:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.StopBits`
        :description: QtSerialPort/QSerialPort-stopBits-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.waitForBytesWritten
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-waitForBytesWritten-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.waitForReadyRead
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtSerialPort/QSerialPort-waitForReadyRead-f.rst

    .. sip:method:: PyQt5.QtSerialPort.QSerialPort.writeData
        :args:
            bytes
        :returns:
            int
        :description: QtSerialPort/QSerialPort-writeData-f.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.baudRateChanged
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Directions`, :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Direction`]
        :description: QtSerialPort/QSerialPort-baudRateChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.breakEnabledChanged
        :args:
            bool
        :description: QtSerialPort/QSerialPort-breakEnabledChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.dataBitsChanged
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.DataBits`
        :description: QtSerialPort/QSerialPort-dataBitsChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.dataErrorPolicyChanged
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.DataErrorPolicy`
        :description: QtSerialPort/QSerialPort-dataErrorPolicyChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.dataTerminalReadyChanged
        :args:
            bool
        :description: QtSerialPort/QSerialPort-dataTerminalReadyChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.error
        :description: QtSerialPort/QSerialPort-error-f-1.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.error
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.SerialPortError`
        :description: QtSerialPort/QSerialPort-error-f.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.errorOccurred
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.SerialPortError`
        :description: QtSerialPort/QSerialPort-errorOccurred-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.flowControlChanged
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.FlowControl`
        :description: QtSerialPort/QSerialPort-flowControlChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.parityChanged
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.Parity`
        :description: QtSerialPort/QSerialPort-parityChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.requestToSendChanged
        :args:
            bool
        :description: QtSerialPort/QSerialPort-requestToSendChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.settingsRestoredOnCloseChanged
        :args:
            bool
        :description: QtSerialPort/QSerialPort-settingsRestoredOnCloseChanged-s.rst

    .. sip:signal:: PyQt5.QtSerialPort.QSerialPort.stopBitsChanged
        :args:
            :sip:ref:`~PyQt5.QtSerialPort.QSerialPort.StopBits`
        :description: QtSerialPort/QSerialPort-stopBitsChanged-s.rst
