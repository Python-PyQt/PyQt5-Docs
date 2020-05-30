:orphan:

.. sip:class:: PyQt5.Qt3DRender.QMesh
    :inherits: :sip:ref:`~PyQt5.Qt3DRender.QGeometryRenderer`
    :description: Qt3DRender/QMesh-c.rst

    .. sip:enum:: PyQt5.Qt3DRender.QMesh.Status
        :description: Qt3DRender/QMesh-Status-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMesh.Status.Error
            :description: Qt3DRender/QMesh-Status-Error-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMesh.Status.Loading
            :description: Qt3DRender/QMesh-Status-Loading-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMesh.Status.None_
            :description: Qt3DRender/QMesh-Status-None_-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QMesh.Status.Ready
            :description: Qt3DRender/QMesh-Status-Ready-v.rst

    .. sip:method:: PyQt5.Qt3DRender.QMesh.__init__
        :args:
            parent: :sip:ref:`~PyQt5.Qt3DCore.QNode` = None
        :description: Qt3DRender/QMesh-__init__-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMesh.meshName
        :returns:
            str
        :description: Qt3DRender/QMesh-meshName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMesh.sceneChangeEvent
        :args:
            :sip:ref:`~PyQt5.Qt3DCore.QSceneChange`
        :description: Qt3DRender/QMesh-sceneChangeEvent-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMesh.setMeshName
        :args:
            str
        :description: Qt3DRender/QMesh-setMeshName-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMesh.setSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: Qt3DRender/QMesh-setSource-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMesh.source
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: Qt3DRender/QMesh-source-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QMesh.status
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QMesh.Status`
        :description: Qt3DRender/QMesh-status-f.rst

    .. sip:signal:: PyQt5.Qt3DRender.QMesh.meshNameChanged
        :args:
            str
        :description: Qt3DRender/QMesh-meshNameChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QMesh.sourceChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: Qt3DRender/QMesh-sourceChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QMesh.statusChanged
        :args:
            :sip:ref:`~PyQt5.Qt3DRender.QMesh.Status`
        :description: Qt3DRender/QMesh-statusChanged-s.rst
