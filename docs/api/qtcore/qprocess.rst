:orphan:

.. sip:class:: PyQt5.QtCore.QProcess
    :inherits: :sip:ref:`~PyQt5.QtCore.QIODevice`
    :description: QtCore/QProcess-c.rst

    .. sip:enum:: PyQt5.QtCore.QProcess.ExitStatus
        :description: QtCore/QProcess-ExitStatus-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ExitStatus.CrashExit
            :description: QtCore/QProcess-ExitStatus-CrashExit-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ExitStatus.NormalExit
            :description: QtCore/QProcess-ExitStatus-NormalExit-v.rst

    .. sip:enum:: PyQt5.QtCore.QProcess.InputChannelMode
        :description: QtCore/QProcess-InputChannelMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.InputChannelMode.ForwardedInputChannel
            :description: QtCore/QProcess-InputChannelMode-ForwardedInputChannel-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.InputChannelMode.ManagedInputChannel
            :description: QtCore/QProcess-InputChannelMode-ManagedInputChannel-v.rst

    .. sip:enum:: PyQt5.QtCore.QProcess.ProcessChannel
        :description: QtCore/QProcess-ProcessChannel-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessChannel.StandardError
            :description: QtCore/QProcess-ProcessChannel-StandardError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessChannel.StandardOutput
            :description: QtCore/QProcess-ProcessChannel-StandardOutput-v.rst

    .. sip:enum:: PyQt5.QtCore.QProcess.ProcessChannelMode
        :description: QtCore/QProcess-ProcessChannelMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessChannelMode.ForwardedChannels
            :description: QtCore/QProcess-ProcessChannelMode-ForwardedChannels-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessChannelMode.ForwardedErrorChannel
            :description: QtCore/QProcess-ProcessChannelMode-ForwardedErrorChannel-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessChannelMode.ForwardedOutputChannel
            :description: QtCore/QProcess-ProcessChannelMode-ForwardedOutputChannel-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessChannelMode.MergedChannels
            :description: QtCore/QProcess-ProcessChannelMode-MergedChannels-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessChannelMode.SeparateChannels
            :description: QtCore/QProcess-ProcessChannelMode-SeparateChannels-v.rst

    .. sip:enum:: PyQt5.QtCore.QProcess.ProcessError
        :description: QtCore/QProcess-ProcessError-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessError.Crashed
            :description: QtCore/QProcess-ProcessError-Crashed-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessError.FailedToStart
            :description: QtCore/QProcess-ProcessError-FailedToStart-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessError.ReadError
            :description: QtCore/QProcess-ProcessError-ReadError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessError.Timedout
            :description: QtCore/QProcess-ProcessError-Timedout-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessError.UnknownError
            :description: QtCore/QProcess-ProcessError-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessError.WriteError
            :description: QtCore/QProcess-ProcessError-WriteError-v.rst

    .. sip:enum:: PyQt5.QtCore.QProcess.ProcessState
        :description: QtCore/QProcess-ProcessState-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessState.NotRunning
            :description: QtCore/QProcess-ProcessState-NotRunning-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessState.Running
            :description: QtCore/QProcess-ProcessState-Running-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QProcess.ProcessState.Starting
            :description: QtCore/QProcess-ProcessState-Starting-v.rst

    .. sip:method:: PyQt5.QtCore.QProcess.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QProcess-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.arguments
        :returns:
            List[str]
        :description: QtCore/QProcess-arguments-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.atEnd
        :returns:
            bool
        :description: QtCore/QProcess-atEnd-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.bytesAvailable
        :returns:
            int
        :description: QtCore/QProcess-bytesAvailable-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.bytesToWrite
        :returns:
            int
        :description: QtCore/QProcess-bytesToWrite-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.canReadLine
        :returns:
            bool
        :description: QtCore/QProcess-canReadLine-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.close
        :description: QtCore/QProcess-close-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.closeReadChannel
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessChannel`
        :description: QtCore/QProcess-closeReadChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.closeWriteChannel
        :description: QtCore/QProcess-closeWriteChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.error
        :returns:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessError`
        :description: QtCore/QProcess-error-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.execute
        :args:
            str
        :returns:
            int
        :static:
        :description: QtCore/QProcess-execute-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.execute
        :args:
            str
            Iterable[str]
        :returns:
            int
        :static:
        :description: QtCore/QProcess-execute-f-1.rst

    .. sip:method:: PyQt5.QtCore.QProcess.exitCode
        :returns:
            int
        :description: QtCore/QProcess-exitCode-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.exitStatus
        :returns:
            :sip:ref:`~PyQt5.QtCore.QProcess.ExitStatus`
        :description: QtCore/QProcess-exitStatus-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.inputChannelMode
        :returns:
            :sip:ref:`~PyQt5.QtCore.QProcess.InputChannelMode`
        :description: QtCore/QProcess-inputChannelMode-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.isSequential
        :returns:
            bool
        :description: QtCore/QProcess-isSequential-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.kill
        :description: QtCore/QProcess-kill-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.nullDevice
        :returns:
            str
        :static:
        :description: QtCore/QProcess-nullDevice-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.open
        :args:
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :returns:
            bool
        :description: QtCore/QProcess-open-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.pid
        :returns:
            int
        :description: QtCore/QProcess-pid-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.processChannelMode
        :returns:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessChannelMode`
        :description: QtCore/QProcess-processChannelMode-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.processEnvironment
        :returns:
            :sip:ref:`~PyQt5.QtCore.QProcessEnvironment`
        :description: QtCore/QProcess-processEnvironment-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.processId
        :returns:
            int
        :description: QtCore/QProcess-processId-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.program
        :returns:
            str
        :description: QtCore/QProcess-program-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.readAllStandardError
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QProcess-readAllStandardError-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.readAllStandardOutput
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QProcess-readAllStandardOutput-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.readChannel
        :returns:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessChannel`
        :description: QtCore/QProcess-readChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.readData
        :args:
            int
        :returns:
            bytes
        :description: QtCore/QProcess-readData-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setArguments
        :args:
            Iterable[str]
        :description: QtCore/QProcess-setArguments-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setInputChannelMode
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.InputChannelMode`
        :description: QtCore/QProcess-setInputChannelMode-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setProcessChannelMode
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessChannelMode`
        :description: QtCore/QProcess-setProcessChannelMode-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setProcessEnvironment
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcessEnvironment`
        :description: QtCore/QProcess-setProcessEnvironment-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setProcessState
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessState`
        :description: QtCore/QProcess-setProcessState-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setProgram
        :args:
            str
        :description: QtCore/QProcess-setProgram-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setReadChannel
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessChannel`
        :description: QtCore/QProcess-setReadChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setStandardErrorFile
        :args:
            str
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.Truncate`
        :description: QtCore/QProcess-setStandardErrorFile-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setStandardInputFile
        :args:
            str
        :description: QtCore/QProcess-setStandardInputFile-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setStandardOutputFile
        :args:
            str
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.Truncate`
        :description: QtCore/QProcess-setStandardOutputFile-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setStandardOutputProcess
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess`
        :description: QtCore/QProcess-setStandardOutputProcess-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setupChildProcess
        :description: QtCore/QProcess-setupChildProcess-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.setWorkingDirectory
        :args:
            str
        :description: QtCore/QProcess-setWorkingDirectory-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.start
        :args:
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtCore/QProcess-start-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.start
        :args:
            str
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtCore/QProcess-start-f-1.rst

    .. sip:method:: PyQt5.QtCore.QProcess.start
        :args:
            str
            Iterable[str]
            mode: Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`] = :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite`
        :description: QtCore/QProcess-start-f-2.rst

    .. sip:method:: PyQt5.QtCore.QProcess.startDetached
        :returns:
            bool
            int
        :description: QtCore/QProcess-startDetached-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.startDetached
        :args:
            str
        :returns:
            bool
        :static:
        :description: QtCore/QProcess-startDetached-f-1.rst

    .. sip:method:: PyQt5.QtCore.QProcess.startDetached
        :args:
            str
            Iterable[str]
        :returns:
            bool
        :static:
        :description: QtCore/QProcess-startDetached-f-2.rst

    .. sip:method:: PyQt5.QtCore.QProcess.startDetached
        :args:
            str
            Iterable[str]
            str
        :returns:
            bool
            int
        :static:
        :description: QtCore/QProcess-startDetached-f-3.rst

    .. sip:method:: PyQt5.QtCore.QProcess.state
        :returns:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessState`
        :description: QtCore/QProcess-state-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.systemEnvironment
        :returns:
            List[str]
        :static:
        :description: QtCore/QProcess-systemEnvironment-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.terminate
        :description: QtCore/QProcess-terminate-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.waitForBytesWritten
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtCore/QProcess-waitForBytesWritten-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.waitForFinished
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtCore/QProcess-waitForFinished-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.waitForReadyRead
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtCore/QProcess-waitForReadyRead-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.waitForStarted
        :args:
            msecs: int = 30000
        :returns:
            bool
        :description: QtCore/QProcess-waitForStarted-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.workingDirectory
        :returns:
            str
        :description: QtCore/QProcess-workingDirectory-f.rst

    .. sip:method:: PyQt5.QtCore.QProcess.writeData
        :args:
            bytes
        :returns:
            int
        :description: QtCore/QProcess-writeData-f.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.error
        :description: QtCore/QProcess-error-f-1.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.error
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessError`
        :description: QtCore/QProcess-error-f.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.errorOccurred
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessError`
        :description: QtCore/QProcess-errorOccurred-s.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.finished
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QProcess.ExitStatus`
        :description: QtCore/QProcess-finished-s.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.readyReadStandardError
        :description: QtCore/QProcess-readyReadStandardError-s.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.readyReadStandardOutput
        :description: QtCore/QProcess-readyReadStandardOutput-s.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.started
        :description: QtCore/QProcess-started-s.rst

    .. sip:signal:: PyQt5.QtCore.QProcess.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QProcess.ProcessState`
        :description: QtCore/QProcess-stateChanged-s.rst
