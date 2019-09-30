:orphan:

.. sip:class:: PyQt5.QtCore.QObject
    :description: QtCore/QObject-c.rst

    .. sip:attribute:: PyQt5.QtCore.QObject.staticMetaObject
        :type: :sip:ref:`~PyQt5.QtCore.QMetaObject`
        :const:
        :static:
        :description: QtCore/QObject-staticMetaObject-a.rst

    .. sip:method:: PyQt5.QtCore.QObject.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QObject-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.blockSignals
        :args:
            bool
        :returns:
            bool
        :description: QtCore/QObject-blockSignals-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.childEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QChildEvent`
        :description: QtCore/QObject-childEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.children
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QObject`]
        :description: QtCore/QObject-children-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.connectNotify
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaMethod`
        :description: QtCore/QObject-connectNotify-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.customEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QObject-customEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.deleteLater
        :description: QtCore/QObject-deleteLater-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.disconnect
        :description: QtCore/QObject-disconnect-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.disconnect
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaObject.Connection`
        :returns:
            bool
        :static:
        :description: QtCore/QObject-disconnect-f-1.rst

    .. sip:method:: PyQt5.QtCore.QObject.disconnectNotify
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaMethod`
        :description: QtCore/QObject-disconnectNotify-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.dumpObjectInfo
        :description: QtCore/QObject-dumpObjectInfo-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.dumpObjectTree
        :description: QtCore/QObject-dumpObjectTree-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.dynamicPropertyNames
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtCore/QObject-dynamicPropertyNames-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QObject-event-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QObject-eventFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChild
        :args:
            type
            name: str = ''
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QObject-findChild-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChild
        :args:
            tuple
            name: str = ''
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QObject-findChild-f-1.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChildren
        :args:
            type
            name: str = ''
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QObject`]
        :description: QtCore/QObject-findChildren-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChildren
        :args:
            tuple
            name: str = ''
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QObject`]
        :description: QtCore/QObject-findChildren-f-1.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChildren
        :args:
            type
            :sip:ref:`~PyQt5.QtCore.QRegExp`
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QObject`]
        :description: QtCore/QObject-findChildren-f-2.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChildren
        :args:
            tuple
            :sip:ref:`~PyQt5.QtCore.QRegExp`
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QObject`]
        :description: QtCore/QObject-findChildren-f-3.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChildren
        :args:
            type
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QObject`]
        :description: QtCore/QObject-findChildren-f-4.rst

    .. sip:method:: PyQt5.QtCore.QObject.findChildren
        :args:
            tuple
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
            options: Union[:sip:ref:`~PyQt5.QtCore.Qt.FindChildOptions`, :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption`] = :sip:ref:`~PyQt5.QtCore.Qt.FindChildOption.FindChildrenRecursively`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QObject`]
        :description: QtCore/QObject-findChildren-f-5.rst

    .. sip:method:: PyQt5.QtCore.QObject.__getattr__
        :args:
            str
        :returns:
            object
        :description: QtCore/QObject-__getattr__-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.inherits
        :args:
            str
        :returns:
            bool
        :description: QtCore/QObject-inherits-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.installEventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QObject-installEventFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.isSignalConnected
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaMethod`
        :returns:
            bool
        :description: QtCore/QObject-isSignalConnected-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.isWidgetType
        :returns:
            bool
        :description: QtCore/QObject-isWidgetType-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.isWindowType
        :returns:
            bool
        :description: QtCore/QObject-isWindowType-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.killTimer
        :args:
            int
        :description: QtCore/QObject-killTimer-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.metaObject
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMetaObject`
        :description: QtCore/QObject-metaObject-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.moveToThread
        :args:
            :sip:ref:`~PyQt5.QtCore.QThread`
        :description: QtCore/QObject-moveToThread-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.objectName
        :returns:
            str
        :description: QtCore/QObject-objectName-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.parent
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QObject-parent-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.property
        :args:
            str
        :returns:
            Any
        :description: QtCore/QObject-property-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.pyqtConfigure
        :args:
            object
        :description: QtCore/QObject-pyqtConfigure-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.receivers
        :args:
            PYQT_SIGNAL
        :returns:
            int
        :description: QtCore/QObject-receivers-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.removeEventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QObject-removeEventFilter-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.sender
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QObject-sender-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.senderSignalIndex
        :returns:
            int
        :description: QtCore/QObject-senderSignalIndex-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.setObjectName
        :args:
            str
        :description: QtCore/QObject-setObjectName-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.setParent
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtCore/QObject-setParent-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.setProperty
        :args:
            str
            Any
        :returns:
            bool
        :description: QtCore/QObject-setProperty-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.signalsBlocked
        :returns:
            bool
        :description: QtCore/QObject-signalsBlocked-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.startTimer
        :args:
            int
            timerType: :sip:ref:`~PyQt5.QtCore.Qt.TimerType` = :sip:ref:`~PyQt5.QtCore.Qt.TimerType.CoarseTimer`
        :returns:
            int
        :description: QtCore/QObject-startTimer-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.thread
        :returns:
            :sip:ref:`~PyQt5.QtCore.QThread`
        :description: QtCore/QObject-thread-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtCore/QObject-timerEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QObject.tr
        :args:
            str
            disambiguation: str = None
            n: int = -1
        :returns:
            str
        :description: QtCore/QObject-tr-f.rst

    .. sip:signal:: PyQt5.QtCore.QObject.destroyed
        :args:
            object: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QObject-destroyed-s.rst

    .. sip:signal:: PyQt5.QtCore.QObject.objectNameChanged
        :args:
            str
        :description: QtCore/QObject-objectNameChanged-s.rst
