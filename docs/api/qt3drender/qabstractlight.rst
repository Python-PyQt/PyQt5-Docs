:orphan:

.. sip:class:: PyQt5.Qt3DRender.QAbstractLight
    :inherits: :sip:ref:`~PyQt5.Qt3DCore.QComponent`
    :description: Qt3DRender/QAbstractLight-c.rst

    .. sip:enum:: PyQt5.Qt3DRender.QAbstractLight.Type
        :description: Qt3DRender/QAbstractLight-Type-e.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAbstractLight.Type.DirectionalLight
            :description: Qt3DRender/QAbstractLight-Type-DirectionalLight-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAbstractLight.Type.PointLight
            :description: Qt3DRender/QAbstractLight-Type-PointLight-v.rst

        .. sip:enum-member:: PyQt5.Qt3DRender.QAbstractLight.Type.SpotLight
            :description: Qt3DRender/QAbstractLight-Type-SpotLight-v.rst

    .. sip:method:: PyQt5.Qt3DRender.QAbstractLight.color
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: Qt3DRender/QAbstractLight-color-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAbstractLight.intensity
        :returns:
            float
        :description: Qt3DRender/QAbstractLight-intensity-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAbstractLight.setColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: Qt3DRender/QAbstractLight-setColor-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAbstractLight.setIntensity
        :args:
            float
        :description: Qt3DRender/QAbstractLight-setIntensity-f.rst

    .. sip:method:: PyQt5.Qt3DRender.QAbstractLight.type
        :returns:
            :sip:ref:`~PyQt5.Qt3DRender.QAbstractLight.Type`
        :description: Qt3DRender/QAbstractLight-type-f.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAbstractLight.colorChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: Qt3DRender/QAbstractLight-colorChanged-s.rst

    .. sip:signal:: PyQt5.Qt3DRender.QAbstractLight.intensityChanged
        :args:
            float
        :description: Qt3DRender/QAbstractLight-intensityChanged-s.rst
