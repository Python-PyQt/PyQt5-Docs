:orphan:

.. sip:class:: PyQt5.QtQuick.QSGAbstractRenderer
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtQuick/QSGAbstractRenderer-c.rst

    .. sip:enum:: PyQt5.QtQuick.QSGAbstractRenderer.ClearModeBit
        :description: QtQuick/QSGAbstractRenderer-ClearModeBit-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGAbstractRenderer.ClearModeBit.ClearColorBuffer
            :description: QtQuick/QSGAbstractRenderer-ClearModeBit-ClearColorBuffer-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGAbstractRenderer.ClearModeBit.ClearDepthBuffer
            :description: QtQuick/QSGAbstractRenderer-ClearModeBit-ClearDepthBuffer-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGAbstractRenderer.ClearModeBit.ClearStencilBuffer
            :description: QtQuick/QSGAbstractRenderer-ClearModeBit-ClearStencilBuffer-v.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.clearColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtQuick/QSGAbstractRenderer-clearColor-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.clearMode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGAbstractRenderer.ClearMode`
        :description: QtQuick/QSGAbstractRenderer-clearMode-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.deviceRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtQuick/QSGAbstractRenderer-deviceRect-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.projectionMatrix
        :returns:
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
        :description: QtQuick/QSGAbstractRenderer-projectionMatrix-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.renderScene
        :args:
            fboId: int = 0
        :description: QtQuick/QSGAbstractRenderer-renderScene-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setClearColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtQuick/QSGAbstractRenderer-setClearColor-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setClearMode
        :args:
            Union[:sip:ref:`~PyQt5.QtQuick.QSGAbstractRenderer.ClearMode`, :sip:ref:`~PyQt5.QtQuick.QSGAbstractRenderer.ClearModeBit`]
        :description: QtQuick/QSGAbstractRenderer-setClearMode-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setDeviceRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtQuick/QSGAbstractRenderer-setDeviceRect-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setDeviceRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtQuick/QSGAbstractRenderer-setDeviceRect-f-1.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setProjectionMatrix
        :args:
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
        :description: QtQuick/QSGAbstractRenderer-setProjectionMatrix-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setProjectionMatrixToRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtQuick/QSGAbstractRenderer-setProjectionMatrixToRect-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setViewportRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtQuick/QSGAbstractRenderer-setViewportRect-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.setViewportRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtQuick/QSGAbstractRenderer-setViewportRect-f-1.rst

    .. sip:method:: PyQt5.QtQuick.QSGAbstractRenderer.viewportRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtQuick/QSGAbstractRenderer-viewportRect-f.rst

    .. sip:signal:: PyQt5.QtQuick.QSGAbstractRenderer.sceneGraphChanged
        :description: QtQuick/QSGAbstractRenderer-sceneGraphChanged-s.rst
