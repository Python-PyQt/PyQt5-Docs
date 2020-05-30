:orphan:

.. sip:class:: PyQt5.QtQuick3D.QQuick3DGeometry
    :inherits: :sip:ref:`~PyQt5.QtQuick3D.QQuick3DObject`
    :description: QtQuick3D/QQuick3DGeometry-c.rst

    .. sip:enum:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType
        :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-e.rst

        .. sip:enum-member:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType.Lines
            :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-Lines-v.rst

        .. sip:enum-member:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType.LineStrip
            :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-LineStrip-v.rst

        .. sip:enum-member:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType.Points
            :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-Points-v.rst

        .. sip:enum-member:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType.TriangleFan
            :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-TriangleFan-v.rst

        .. sip:enum-member:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType.Triangles
            :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-Triangles-v.rst

        .. sip:enum-member:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType.TriangleStrip
            :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-TriangleStrip-v.rst

        .. sip:enum-member:: PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType.Unknown
            :description: QtQuick3D/QQuick3DGeometry-PrimitiveType-Unknown-v.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtQuick3D.QQuick3DObject` = None
        :description: QtQuick3D/QQuick3DGeometry-__init__-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.addAttribute
        :args:
            :sip:ref:`~PyQt5.QtQuick3D.QQuick3DGeometry.Attribute`
        :description: QtQuick3D/QQuick3DGeometry-addAttribute-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.addAttribute
        :args:
            :sip:ref:`~PyQt5.QtQuick3D.QQuick3DGeometry.Attribute.Semantic`
            int
            :sip:ref:`~PyQt5.QtQuick3D.QQuick3DGeometry.Attribute.ComponentType`
        :description: QtQuick3D/QQuick3DGeometry-addAttribute-f-1.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.attribute
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtQuick3D.QQuick3DGeometry.Attribute`
        :description: QtQuick3D/QQuick3DGeometry-attribute-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.attributeCount
        :returns:
            int
        :description: QtQuick3D/QQuick3DGeometry-attributeCount-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.boundsMax
        :returns:
            :sip:ref:`~PyQt5.QtGui.QVector3D`
        :description: QtQuick3D/QQuick3DGeometry-boundsMax-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.boundsMin
        :returns:
            :sip:ref:`~PyQt5.QtGui.QVector3D`
        :description: QtQuick3D/QQuick3DGeometry-boundsMin-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.clear
        :description: QtQuick3D/QQuick3DGeometry-clear-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.indexBuffer
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtQuick3D/QQuick3DGeometry-indexBuffer-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.name
        :returns:
            str
        :description: QtQuick3D/QQuick3DGeometry-name-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.primitiveType
        :returns:
            :sip:ref:`~PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType`
        :description: QtQuick3D/QQuick3DGeometry-primitiveType-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.setBounds
        :args:
            :sip:ref:`~PyQt5.QtGui.QVector3D`
            :sip:ref:`~PyQt5.QtGui.QVector3D`
        :description: QtQuick3D/QQuick3DGeometry-setBounds-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.setIndexData
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtQuick3D/QQuick3DGeometry-setIndexData-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.setName
        :args:
            str
        :description: QtQuick3D/QQuick3DGeometry-setName-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.setPrimitiveType
        :args:
            :sip:ref:`~PyQt5.QtQuick3D.QQuick3DGeometry.PrimitiveType`
        :description: QtQuick3D/QQuick3DGeometry-setPrimitiveType-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.setStride
        :args:
            int
        :description: QtQuick3D/QQuick3DGeometry-setStride-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.setVertexData
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtQuick3D/QQuick3DGeometry-setVertexData-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.stride
        :returns:
            int
        :description: QtQuick3D/QQuick3DGeometry-stride-f.rst

    .. sip:method:: PyQt5.QtQuick3D.QQuick3DGeometry.vertexBuffer
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtQuick3D/QQuick3DGeometry-vertexBuffer-f.rst

    .. sip:signal:: PyQt5.QtQuick3D.QQuick3DGeometry.nameChanged
        :description: QtQuick3D/QQuick3DGeometry-nameChanged-s.rst
