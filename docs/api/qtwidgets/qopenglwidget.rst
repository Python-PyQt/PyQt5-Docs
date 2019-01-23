:orphan:

.. sip:class:: PyQt5.QtWidgets.QOpenGLWidget
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QOpenGLWidget-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QOpenGLWidget.UpdateBehavior
        :description: QtWidgets/QOpenGLWidget-UpdateBehavior-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QOpenGLWidget.UpdateBehavior.NoPartialUpdate
            :description: QtWidgets/QOpenGLWidget-UpdateBehavior-NoPartialUpdate-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QOpenGLWidget.UpdateBehavior.PartialUpdate
            :description: QtWidgets/QOpenGLWidget-UpdateBehavior-PartialUpdate-v.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QOpenGLWidget-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.context
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtWidgets/QOpenGLWidget-context-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.defaultFramebufferObject
        :returns:
            int
        :description: QtWidgets/QOpenGLWidget-defaultFramebufferObject-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.doneCurrent
        :description: QtWidgets/QOpenGLWidget-doneCurrent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QOpenGLWidget-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.format
        :returns:
            :sip:ref:`~PyQt5.QtGui.QSurfaceFormat`
        :description: QtWidgets/QOpenGLWidget-format-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.grabFramebuffer
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtWidgets/QOpenGLWidget-grabFramebuffer-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.initializeGL
        :description: QtWidgets/QOpenGLWidget-initializeGL-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.isValid
        :returns:
            bool
        :description: QtWidgets/QOpenGLWidget-isValid-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.makeCurrent
        :description: QtWidgets/QOpenGLWidget-makeCurrent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.metric
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintDevice.PaintDeviceMetric`
        :returns:
            int
        :description: QtWidgets/QOpenGLWidget-metric-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.paintEngine
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPaintEngine`
        :description: QtWidgets/QOpenGLWidget-paintEngine-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QOpenGLWidget-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.paintGL
        :description: QtWidgets/QOpenGLWidget-paintGL-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtWidgets/QOpenGLWidget-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.resizeGL
        :args:
            int
            int
        :description: QtWidgets/QOpenGLWidget-resizeGL-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.setFormat
        :args:
            :sip:ref:`~PyQt5.QtGui.QSurfaceFormat`
        :description: QtWidgets/QOpenGLWidget-setFormat-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.setTextureFormat
        :args:
            int
        :description: QtWidgets/QOpenGLWidget-setTextureFormat-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.setUpdateBehavior
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QOpenGLWidget.UpdateBehavior`
        :description: QtWidgets/QOpenGLWidget-setUpdateBehavior-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.textureFormat
        :returns:
            int
        :description: QtWidgets/QOpenGLWidget-textureFormat-f.rst

    .. sip:method:: PyQt5.QtWidgets.QOpenGLWidget.updateBehavior
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QOpenGLWidget.UpdateBehavior`
        :description: QtWidgets/QOpenGLWidget-updateBehavior-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QOpenGLWidget.aboutToCompose
        :description: QtWidgets/QOpenGLWidget-aboutToCompose-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QOpenGLWidget.aboutToResize
        :description: QtWidgets/QOpenGLWidget-aboutToResize-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QOpenGLWidget.frameSwapped
        :description: QtWidgets/QOpenGLWidget-frameSwapped-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QOpenGLWidget.resized
        :description: QtWidgets/QOpenGLWidget-resized-s.rst
