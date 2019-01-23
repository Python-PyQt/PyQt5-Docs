:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLWindow
    :inherits: :sip:ref:`~PyQt5.QtGui.QPaintDeviceWindow`
    :description: QtGui/QOpenGLWindow-c.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLWindow.UpdateBehavior
        :description: QtGui/QOpenGLWindow-UpdateBehavior-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.NoPartialUpdate
            :description: QtGui/QOpenGLWindow-UpdateBehavior-NoPartialUpdate-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.PartialUpdateBlend
            :description: QtGui/QOpenGLWindow-UpdateBehavior-PartialUpdateBlend-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.PartialUpdateBlit
            :description: QtGui/QOpenGLWindow-UpdateBehavior-PartialUpdateBlit-v.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.__init__
        :args:
            updateBehavior: :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior` = :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.NoPartialUpdate`
            parent: :sip:ref:`~PyQt5.QtGui.QWindow` = None
        :description: QtGui/QOpenGLWindow-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
            updateBehavior: :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior` = :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.NoPartialUpdate`
            parent: :sip:ref:`~PyQt5.QtGui.QWindow` = None
        :description: QtGui/QOpenGLWindow-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.context
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtGui/QOpenGLWindow-context-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.defaultFramebufferObject
        :returns:
            int
        :description: QtGui/QOpenGLWindow-defaultFramebufferObject-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.doneCurrent
        :description: QtGui/QOpenGLWindow-doneCurrent-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.grabFramebuffer
        :returns:
            :sip:ref:`~PyQt5.QtGui.QImage`
        :description: QtGui/QOpenGLWindow-grabFramebuffer-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.initializeGL
        :description: QtGui/QOpenGLWindow-initializeGL-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.isValid
        :returns:
            bool
        :description: QtGui/QOpenGLWindow-isValid-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.makeCurrent
        :description: QtGui/QOpenGLWindow-makeCurrent-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.metric
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintDevice.PaintDeviceMetric`
        :returns:
            int
        :description: QtGui/QOpenGLWindow-metric-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtGui/QOpenGLWindow-paintEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.paintGL
        :description: QtGui/QOpenGLWindow-paintGL-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.paintOverGL
        :description: QtGui/QOpenGLWindow-paintOverGL-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.paintUnderGL
        :description: QtGui/QOpenGLWindow-paintUnderGL-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtGui/QOpenGLWindow-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.resizeGL
        :args:
            int
            int
        :description: QtGui/QOpenGLWindow-resizeGL-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.shareContext
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtGui/QOpenGLWindow-shareContext-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLWindow.updateBehavior
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior`
        :description: QtGui/QOpenGLWindow-updateBehavior-f.rst

    .. sip:signal:: PyQt5.QtGui.QOpenGLWindow.frameSwapped
        :description: QtGui/QOpenGLWindow-frameSwapped-s.rst
