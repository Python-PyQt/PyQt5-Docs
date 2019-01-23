:orphan:

.. sip:class:: PyQt5.Qt3DCore.QNode
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: Qt3DCore/QNode-c.rst

    .. sip:enum:: PyQt5.Qt3DCore.QNode.PropertyTrackingMode
        :description: Qt3DCore/QNode-PropertyTrackingMode-e.rst

        .. sip:enum-member:: PyQt5.Qt3DCore.QNode.PropertyTrackingMode.DontTrackValues
            :description: Qt3DCore/QNode-PropertyTrackingMode-DontTrackValues-v.rst

        .. sip:enum-member:: PyQt5.Qt3DCore.QNode.PropertyTrackingMode.TrackAllValues
            :description: Qt3DCore/QNode-PropertyTrackingMode-TrackAllValues-v.rst

        .. sip:enum-member:: PyQt5.Qt3DCore.QNode.PropertyTrackingMode.TrackFinalValues
            :description: Qt3DCore/QNode-PropertyTrackingMode-TrackFinalValues-v.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.__init__
        :args:
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DCore/QNode-__init__-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.blockNotifications
        :args:
            bool
        :returns:
            bool
        :description: Qt3DCore/QNode-blockNotifications-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.childNodes
        :returns:
            List[:sip:ref:`~PyQt5.Qt3DCore.QNode`]
        :description: Qt3DCore/QNode-childNodes-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.clearPropertyTracking
        :args:
            str
        :description: Qt3DCore/QNode-clearPropertyTracking-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.clearPropertyTrackings
        :description: Qt3DCore/QNode-clearPropertyTrackings-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.defaultPropertyTrackingMode
        :returns:
            :sip:ref:`~PyQt5.Qt3DCore.QNode.PropertyTrackingMode`
        :description: Qt3DCore/QNode-defaultPropertyTrackingMode-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.id
        :returns:
            :sip:ref:`~PyQt5.Qt3DCore.QNodeId`
        :description: Qt3DCore/QNode-id-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.isEnabled
        :returns:
            bool
        :description: Qt3DCore/QNode-isEnabled-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.notificationsBlocked
        :returns:
            bool
        :description: Qt3DCore/QNode-notificationsBlocked-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.notifyObservers
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QSceneChange`
        :description: Qt3DCore/QNode-notifyObservers-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.parentNode
        :returns:
            :sip:ref:`~PyQt5.Qt3DCore.QNode`
        :description: Qt3DCore/QNode-parentNode-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.propertyTracking
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.Qt3DCore.QNode.PropertyTrackingMode`
        :description: Qt3DCore/QNode-propertyTracking-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.sceneChangeEvent
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QSceneChange`
        :description: Qt3DCore/QNode-sceneChangeEvent-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.sendCommand
        :args:
            str
            data: Any = None
            replyTo: int = Qt3DCore.QNodeCommand.CommandId()
        :returns:
            int
        :description: Qt3DCore/QNode-sendCommand-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.sendReply
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QNodeCommand`
        :description: Qt3DCore/QNode-sendReply-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.setDefaultPropertyTrackingMode
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QNode.PropertyTrackingMode`
        :description: Qt3DCore/QNode-setDefaultPropertyTrackingMode-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.setEnabled
        :args:
            bool
        :description: Qt3DCore/QNode-setEnabled-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.setParent
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QNode`
        :description: Qt3DCore/QNode-setParent-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QNode.setPropertyTracking
        :args:
            str
            :sip:ref:`~PyQt5.Qt3DCore.QNode.PropertyTrackingMode`
        :description: Qt3DCore/QNode-setPropertyTracking-f.rst

    .. sip:signal:: PyQt5.Qt3DCore.QNode.defaultPropertyTrackingModeChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QNode.PropertyTrackingMode`
        :description: Qt3DCore/QNode-defaultPropertyTrackingModeChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DCore.QNode.enabledChanged
        :args:
            bool
        :description: Qt3DCore/QNode-enabledChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DCore.QNode.nodeDestroyed
        :description: Qt3DCore/QNode-nodeDestroyed-s.rst

    .. sip:signal:: PyQt5.Qt3DCore.QNode.parentChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: Qt3DCore/QNode-parentChanged-s.rst
