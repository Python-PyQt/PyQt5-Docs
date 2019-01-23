:orphan:

.. sip:class:: PyQt5.QtCore.QEventLoop
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QEventLoop-c.rst

    .. sip:enum:: PyQt5.QtCore.QEventLoop.ProcessEventsFlag
        :description: QtCore/QEventLoop-ProcessEventsFlag-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QEventLoop.ProcessEventsFlag.AllEvents
            :description: QtCore/QEventLoop-ProcessEventsFlag-AllEvents-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QEventLoop.ProcessEventsFlag.ExcludeSocketNotifiers
            :description: QtCore/QEventLoop-ProcessEventsFlag-ExcludeSocketNotifiers-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QEventLoop.ProcessEventsFlag.ExcludeUserInputEvents
            :description: QtCore/QEventLoop-ProcessEventsFlag-ExcludeUserInputEvents-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QEventLoop.ProcessEventsFlag.WaitForMoreEvents
            :description: QtCore/QEventLoop-ProcessEventsFlag-WaitForMoreEvents-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QEventLoop.ProcessEventsFlag.X11ExcludeTimers
            :description: QtCore/QEventLoop-ProcessEventsFlag-X11ExcludeTimers-v.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QEventLoop-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QEventLoop-event-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.exec
        :args:
            flags: :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlags` = :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag.AllEvents`
        :returns:
            int
        :description: QtCore/QEventLoop-exec-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.exec_
        :args:
            flags: :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlags` = :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag.AllEvents`
        :returns:
            int
        :description: QtCore/QEventLoop-exec_-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.exit
        :args:
            returnCode: int = 0
        :description: QtCore/QEventLoop-exit-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.isRunning
        :returns:
            bool
        :description: QtCore/QEventLoop-isRunning-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.processEvents
        :args:
            flags: Union[:sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlags`, :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag`] = :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag.AllEvents`
        :returns:
            bool
        :description: QtCore/QEventLoop-processEvents-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.processEvents
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlags`, :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag`]
            int
        :description: QtCore/QEventLoop-processEvents-f-1.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.quit
        :description: QtCore/QEventLoop-quit-f.rst

    .. sip:method:: PyQt5.QtCore.QEventLoop.wakeUp
        :description: QtCore/QEventLoop-wakeUp-f.rst
