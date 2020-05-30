:orphan:

.. sip:class:: PyQt5.QtRemoteObjects.QRemoteObjectReplica
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtRemoteObjects/QRemoteObjectReplica-c.rst

    .. sip:enum:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.State
        :description: QtRemoteObjects/QRemoteObjectReplica-State-e.rst

        .. sip:enum-member:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.State.Default
            :description: QtRemoteObjects/QRemoteObjectReplica-State-Default-v.rst

        .. sip:enum-member:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.State.SignatureMismatch
            :description: QtRemoteObjects/QRemoteObjectReplica-State-SignatureMismatch-v.rst

        .. sip:enum-member:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.State.Suspect
            :description: QtRemoteObjects/QRemoteObjectReplica-State-Suspect-v.rst

        .. sip:enum-member:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.State.Uninitialized
            :description: QtRemoteObjects/QRemoteObjectReplica-State-Uninitialized-v.rst

        .. sip:enum-member:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.State.Valid
            :description: QtRemoteObjects/QRemoteObjectReplica-State-Valid-v.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.isInitialized
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectReplica-isInitialized-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.isReplicaValid
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectReplica-isReplicaValid-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.node
        :returns:
            :sip:ref:`~PyQt5.QtRemoteObjects.QRemoteObjectNode`
        :description: QtRemoteObjects/QRemoteObjectReplica-node-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.setNode
        :args:
            :sip:ref:`~PyQt5.QtRemoteObjects.QRemoteObjectNode`
        :description: QtRemoteObjects/QRemoteObjectReplica-setNode-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.state
        :returns:
            :sip:ref:`~PyQt5.QtRemoteObjects.QRemoteObjectReplica.State`
        :description: QtRemoteObjects/QRemoteObjectReplica-state-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.waitForSource
        :args:
            timeout: int = 30000
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectReplica-waitForSource-f.rst

    .. sip:signal:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.initialized
        :description: QtRemoteObjects/QRemoteObjectReplica-initialized-s.rst

    .. sip:signal:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.notified
        :description: QtRemoteObjects/QRemoteObjectReplica-notified-s.rst

    .. sip:signal:: PyQt5.QtRemoteObjects.QRemoteObjectReplica.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtRemoteObjects.QRemoteObjectReplica.State`
            :sip:ref:`~PyQt5.QtRemoteObjects.QRemoteObjectReplica.State`
        :description: QtRemoteObjects/QRemoteObjectReplica-stateChanged-s.rst
