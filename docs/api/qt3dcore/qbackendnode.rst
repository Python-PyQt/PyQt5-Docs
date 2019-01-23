:orphan:

.. sip:class:: PyQt5.Qt3DCore.QBackendNode
    :description: Qt3DCore/QBackendNode-c.rst

    .. sip:enum:: PyQt5.Qt3DCore.QBackendNode.Mode
        :description: Qt3DCore/QBackendNode-Mode-e.rst

        .. sip:enum-member:: PyQt5.Qt3DCore.QBackendNode.Mode.ReadOnly
            :description: Qt3DCore/QBackendNode-Mode-ReadOnly-v.rst

        .. sip:enum-member:: PyQt5.Qt3DCore.QBackendNode.Mode.ReadWrite
            :description: Qt3DCore/QBackendNode-Mode-ReadWrite-v.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.__init__
        :args:
            mode: :sip:ref:`~PyQt5.Qt3DCore.QBackendNode.Mode` = :sip:ref:`~PyQt5.Qt3DCore.QBackendNode.Mode.ReadOnly`
        :description: Qt3DCore/QBackendNode-__init__-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.isEnabled
        :returns:
            bool
        :description: Qt3DCore/QBackendNode-isEnabled-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.mode
        :returns:
            :sip:ref:`~PyQt5.Qt3DCore.QBackendNode.Mode`
        :description: Qt3DCore/QBackendNode-mode-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.notifyObservers
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QSceneChange`
        :description: Qt3DCore/QBackendNode-notifyObservers-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.peerId
        :returns:
            :sip:ref:`~PyQt5.Qt3DCore.QNodeId`
        :description: Qt3DCore/QBackendNode-peerId-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.sceneChangeEvent
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QSceneChange`
        :description: Qt3DCore/QBackendNode-sceneChangeEvent-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.sendCommand
        :args:
            str
            Any
            replyTo: int = Qt3DCore.QNodeCommand.CommandId()
        :returns:
            int
        :description: Qt3DCore/QBackendNode-sendCommand-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.sendReply
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QNodeCommand`
        :description: Qt3DCore/QBackendNode-sendReply-f.rst

    .. sip:method:: PyQt5.Qt3DCore.QBackendNode.setEnabled
        :args:
            bool
        :description: Qt3DCore/QBackendNode-setEnabled-f.rst
