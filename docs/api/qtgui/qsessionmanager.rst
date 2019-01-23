:orphan:

.. sip:class:: PyQt5.QtGui.QSessionManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QSessionManager-c.rst

    .. sip:enum:: PyQt5.QtGui.QSessionManager.RestartHint
        :description: QtGui/QSessionManager-RestartHint-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QSessionManager.RestartHint.RestartAnyway
            :description: QtGui/QSessionManager-RestartHint-RestartAnyway-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QSessionManager.RestartHint.RestartIfRunning
            :description: QtGui/QSessionManager-RestartHint-RestartIfRunning-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QSessionManager.RestartHint.RestartImmediately
            :description: QtGui/QSessionManager-RestartHint-RestartImmediately-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QSessionManager.RestartHint.RestartNever
            :description: QtGui/QSessionManager-RestartHint-RestartNever-v.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.allowsErrorInteraction
        :returns:
            bool
        :description: QtGui/QSessionManager-allowsErrorInteraction-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.allowsInteraction
        :returns:
            bool
        :description: QtGui/QSessionManager-allowsInteraction-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.cancel
        :description: QtGui/QSessionManager-cancel-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.discardCommand
        :returns:
            List[str]
        :description: QtGui/QSessionManager-discardCommand-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.isPhase2
        :returns:
            bool
        :description: QtGui/QSessionManager-isPhase2-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.release
        :description: QtGui/QSessionManager-release-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.requestPhase2
        :description: QtGui/QSessionManager-requestPhase2-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.restartCommand
        :returns:
            List[str]
        :description: QtGui/QSessionManager-restartCommand-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.restartHint
        :returns:
            :sip:ref:`~PyQt5.QtGui.QSessionManager.RestartHint`
        :description: QtGui/QSessionManager-restartHint-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.sessionId
        :returns:
            str
        :description: QtGui/QSessionManager-sessionId-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.sessionKey
        :returns:
            str
        :description: QtGui/QSessionManager-sessionKey-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.setDiscardCommand
        :args:
            Iterable[str]
        :description: QtGui/QSessionManager-setDiscardCommand-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.setManagerProperty
        :args:
            str
            str
        :description: QtGui/QSessionManager-setManagerProperty-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.setManagerProperty
        :args:
            str
            Iterable[str]
        :description: QtGui/QSessionManager-setManagerProperty-f-1.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.setRestartCommand
        :args:
            Iterable[str]
        :description: QtGui/QSessionManager-setRestartCommand-f.rst

    .. sip:method:: PyQt5.QtGui.QSessionManager.setRestartHint
        :args:
            :sip:ref:`~PyQt5.QtGui.QSessionManager.RestartHint`
        :description: QtGui/QSessionManager-setRestartHint-f.rst
