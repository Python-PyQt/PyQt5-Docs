:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLDebugLogger
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QOpenGLDebugLogger-c.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLDebugLogger.LoggingMode
        :description: QtGui/QOpenGLDebugLogger-LoggingMode-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugLogger.LoggingMode.AsynchronousLogging
            :description: QtGui/QOpenGLDebugLogger-LoggingMode-AsynchronousLogging-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugLogger.LoggingMode.SynchronousLogging
            :description: QtGui/QOpenGLDebugLogger-LoggingMode-SynchronousLogging-v.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QOpenGLDebugLogger-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.disableMessages
        :args:
            sources: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Sources`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source.AnySource`
            types: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Types`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type.AnyType`
            severities: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severities`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity.AnySeverity`
        :description: QtGui/QOpenGLDebugLogger-disableMessages-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.disableMessages
        :args:
            Iterable[int]
            sources: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Sources`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source.AnySource`
            types: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Types`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type.AnyType`
        :description: QtGui/QOpenGLDebugLogger-disableMessages-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.enableMessages
        :args:
            sources: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Sources`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source.AnySource`
            types: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Types`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type.AnyType`
            severities: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severities`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity.AnySeverity`
        :description: QtGui/QOpenGLDebugLogger-enableMessages-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.enableMessages
        :args:
            Iterable[int]
            sources: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Sources`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source.AnySource`
            types: Union[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Types`, :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type`] = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type.AnyType`
        :description: QtGui/QOpenGLDebugLogger-enableMessages-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.initialize
        :returns:
            bool
        :description: QtGui/QOpenGLDebugLogger-initialize-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.isLogging
        :returns:
            bool
        :description: QtGui/QOpenGLDebugLogger-isLogging-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.loggedMessages
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`]
        :description: QtGui/QOpenGLDebugLogger-loggedMessages-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.loggingMode
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugLogger.LoggingMode`
        :description: QtGui/QOpenGLDebugLogger-loggingMode-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.logMessage
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :description: QtGui/QOpenGLDebugLogger-logMessage-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.maximumMessageLength
        :returns:
            int
        :description: QtGui/QOpenGLDebugLogger-maximumMessageLength-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.popGroup
        :description: QtGui/QOpenGLDebugLogger-popGroup-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.pushGroup
        :args:
            str
            id: int = 0
            source: :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source` = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source.ApplicationSource`
        :description: QtGui/QOpenGLDebugLogger-pushGroup-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.startLogging
        :args:
            loggingMode: :sip:ref:`~PyQt5.QtGui.QOpenGLDebugLogger.LoggingMode` = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugLogger.LoggingMode.AsynchronousLogging`
        :description: QtGui/QOpenGLDebugLogger-startLogging-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugLogger.stopLogging
        :description: QtGui/QOpenGLDebugLogger-stopLogging-f.rst

    .. sip:signal:: PyQt5.QtGui.QOpenGLDebugLogger.messageLogged
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :description: QtGui/QOpenGLDebugLogger-messageLogged-s.rst
