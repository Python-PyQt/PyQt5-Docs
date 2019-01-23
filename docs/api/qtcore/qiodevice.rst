:orphan:

.. sip:class:: PyQt5.QtCore.QIODevice
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QIODevice-c.rst

    .. sip:enum:: PyQt5.QtCore.QIODevice.OpenModeFlag
        :description: QtCore/QIODevice-OpenModeFlag-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.Append
            :description: QtCore/QIODevice-OpenModeFlag-Append-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.ExistingOnly
            :description: QtCore/QIODevice-OpenModeFlag-ExistingOnly-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.NewOnly
            :description: QtCore/QIODevice-OpenModeFlag-NewOnly-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.NotOpen
            :description: QtCore/QIODevice-OpenModeFlag-NotOpen-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.ReadOnly
            :description: QtCore/QIODevice-OpenModeFlag-ReadOnly-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.ReadWrite
            :description: QtCore/QIODevice-OpenModeFlag-ReadWrite-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.Text
            :description: QtCore/QIODevice-OpenModeFlag-Text-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.Truncate
            :description: QtCore/QIODevice-OpenModeFlag-Truncate-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.Unbuffered
            :description: QtCore/QIODevice-OpenModeFlag-Unbuffered-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QIODevice.OpenModeFlag.WriteOnly
            :description: QtCore/QIODevice-OpenModeFlag-WriteOnly-v.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.__init__
        :description: QtCore/QIODevice-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QIODevice-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.atEnd
        :returns:
            bool
        :description: QtCore/QIODevice-atEnd-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.bytesAvailable
        :returns:
            int
        :description: QtCore/QIODevice-bytesAvailable-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.bytesToWrite
        :returns:
            int
        :description: QtCore/QIODevice-bytesToWrite-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.canReadLine
        :returns:
            bool
        :description: QtCore/QIODevice-canReadLine-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.close
        :description: QtCore/QIODevice-close-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.commitTransaction
        :description: QtCore/QIODevice-commitTransaction-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.currentReadChannel
        :returns:
            int
        :description: QtCore/QIODevice-currentReadChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.currentWriteChannel
        :returns:
            int
        :description: QtCore/QIODevice-currentWriteChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.errorString
        :returns:
            str
        :description: QtCore/QIODevice-errorString-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.getChar
        :returns:
            bool
            str
        :description: QtCore/QIODevice-getChar-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.isOpen
        :returns:
            bool
        :description: QtCore/QIODevice-isOpen-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.isReadable
        :returns:
            bool
        :description: QtCore/QIODevice-isReadable-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.isSequential
        :returns:
            bool
        :description: QtCore/QIODevice-isSequential-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.isTextModeEnabled
        :returns:
            bool
        :description: QtCore/QIODevice-isTextModeEnabled-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.isTransactionStarted
        :returns:
            bool
        :description: QtCore/QIODevice-isTransactionStarted-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.isWritable
        :returns:
            bool
        :description: QtCore/QIODevice-isWritable-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.open
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`]
        :returns:
            bool
        :description: QtCore/QIODevice-open-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.openMode
        :returns:
            :sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`
        :description: QtCore/QIODevice-openMode-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.peek
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QIODevice-peek-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.pos
        :returns:
            int
        :description: QtCore/QIODevice-pos-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.putChar
        :args:
            str
        :returns:
            bool
        :description: QtCore/QIODevice-putChar-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.read
        :args:
            int
        :returns:
            bytes
        :description: QtCore/QIODevice-read-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.readAll
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QIODevice-readAll-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.readChannelCount
        :returns:
            int
        :description: QtCore/QIODevice-readChannelCount-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.readData
        :args:
            int
        :returns:
            bytes
        :description: QtCore/QIODevice-readData-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.readLine
        :args:
            maxlen: int = 0
        :returns:
            bytes
        :description: QtCore/QIODevice-readLine-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.readLineData
        :args:
            int
        :returns:
            bytes
        :description: QtCore/QIODevice-readLineData-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.reset
        :returns:
            bool
        :description: QtCore/QIODevice-reset-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.rollbackTransaction
        :description: QtCore/QIODevice-rollbackTransaction-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.seek
        :args:
            int
        :returns:
            bool
        :description: QtCore/QIODevice-seek-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.setCurrentReadChannel
        :args:
            int
        :description: QtCore/QIODevice-setCurrentReadChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.setCurrentWriteChannel
        :args:
            int
        :description: QtCore/QIODevice-setCurrentWriteChannel-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.setErrorString
        :args:
            str
        :description: QtCore/QIODevice-setErrorString-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.setOpenMode
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QIODevice.OpenMode`, :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag`]
        :description: QtCore/QIODevice-setOpenMode-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.setTextModeEnabled
        :args:
            bool
        :description: QtCore/QIODevice-setTextModeEnabled-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.size
        :returns:
            int
        :description: QtCore/QIODevice-size-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.skip
        :args:
            int
        :returns:
            int
        :description: QtCore/QIODevice-skip-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.startTransaction
        :description: QtCore/QIODevice-startTransaction-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.ungetChar
        :args:
            str
        :description: QtCore/QIODevice-ungetChar-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.waitForBytesWritten
        :args:
            int
        :returns:
            bool
        :description: QtCore/QIODevice-waitForBytesWritten-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.waitForReadyRead
        :args:
            int
        :returns:
            bool
        :description: QtCore/QIODevice-waitForReadyRead-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.write
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            int
        :description: QtCore/QIODevice-write-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.writeChannelCount
        :returns:
            int
        :description: QtCore/QIODevice-writeChannelCount-f.rst

    .. sip:method:: PyQt5.QtCore.QIODevice.writeData
        :args:
            bytes
        :returns:
            int
        :description: QtCore/QIODevice-writeData-f.rst

    .. sip:signal:: PyQt5.QtCore.QIODevice.aboutToClose
        :description: QtCore/QIODevice-aboutToClose-s.rst

    .. sip:signal:: PyQt5.QtCore.QIODevice.bytesWritten
        :args:
            int
        :description: QtCore/QIODevice-bytesWritten-s.rst

    .. sip:signal:: PyQt5.QtCore.QIODevice.channelBytesWritten
        :args:
            int
            int
        :description: QtCore/QIODevice-channelBytesWritten-s.rst

    .. sip:signal:: PyQt5.QtCore.QIODevice.channelReadyRead
        :args:
            int
        :description: QtCore/QIODevice-channelReadyRead-s.rst

    .. sip:signal:: PyQt5.QtCore.QIODevice.readChannelFinished
        :description: QtCore/QIODevice-readChannelFinished-s.rst

    .. sip:signal:: PyQt5.QtCore.QIODevice.readyRead
        :description: QtCore/QIODevice-readyRead-s.rst
