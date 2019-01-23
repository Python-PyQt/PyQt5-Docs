:orphan:

.. sip:class:: PyQt5.QtCore.QAbstractEventDispatcher
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QAbstractEventDispatcher-c.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QAbstractEventDispatcher-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.closingDown
        :description: QtCore/QAbstractEventDispatcher-closingDown-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.filterNativeEvent
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            sip.voidptr
        :returns:
            bool
            int
        :description: QtCore/QAbstractEventDispatcher-filterNativeEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.flush
        :description: QtCore/QAbstractEventDispatcher-flush-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.hasPendingEvents
        :returns:
            bool
        :description: QtCore/QAbstractEventDispatcher-hasPendingEvents-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.installNativeEventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter`
        :description: QtCore/QAbstractEventDispatcher-installNativeEventFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.instance
        :args:
            thread: :sip:ref:`~PyQt5.QtCore.QThread` = None
        :returns:
            :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher`
        :static:
        :description: QtCore/QAbstractEventDispatcher-instance-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.interrupt
        :description: QtCore/QAbstractEventDispatcher-interrupt-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.processEvents
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlags`, :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag`]
        :returns:
            bool
        :description: QtCore/QAbstractEventDispatcher-processEvents-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.registeredTimers
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher.TimerInfo`]
        :description: QtCore/QAbstractEventDispatcher-registeredTimers-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.registerEventNotifier
        :args:
            :sip:ref:`~PyQt5.QtCore.QWinEventNotifier`
        :returns:
            bool
        :description: QtCore/QAbstractEventDispatcher-registerEventNotifier-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.registerSocketNotifier
        :args:
            :sip:ref:`~PyQt5.QtCore.QSocketNotifier`
        :description: QtCore/QAbstractEventDispatcher-registerSocketNotifier-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.registerTimer
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.Qt.TimerType`
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            int
        :description: QtCore/QAbstractEventDispatcher-registerTimer-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.registerTimer
        :args:
            int
            int
            :sip:ref:`~PyQt5.QtCore.Qt.TimerType`
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QAbstractEventDispatcher-registerTimer-f-1.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.remainingTime
        :args:
            int
        :returns:
            int
        :description: QtCore/QAbstractEventDispatcher-remainingTime-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.removeNativeEventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter`
        :description: QtCore/QAbstractEventDispatcher-removeNativeEventFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.startingUp
        :description: QtCore/QAbstractEventDispatcher-startingUp-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.unregisterEventNotifier
        :args:
            :sip:ref:`~PyQt5.QtCore.QWinEventNotifier`
        :description: QtCore/QAbstractEventDispatcher-unregisterEventNotifier-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.unregisterSocketNotifier
        :args:
            :sip:ref:`~PyQt5.QtCore.QSocketNotifier`
        :description: QtCore/QAbstractEventDispatcher-unregisterSocketNotifier-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.unregisterTimer
        :args:
            int
        :returns:
            bool
        :description: QtCore/QAbstractEventDispatcher-unregisterTimer-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.unregisterTimers
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            bool
        :description: QtCore/QAbstractEventDispatcher-unregisterTimers-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractEventDispatcher.wakeUp
        :description: QtCore/QAbstractEventDispatcher-wakeUp-f.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractEventDispatcher.aboutToBlock
        :description: QtCore/QAbstractEventDispatcher-aboutToBlock-s.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractEventDispatcher.awake
        :description: QtCore/QAbstractEventDispatcher-awake-s.rst
