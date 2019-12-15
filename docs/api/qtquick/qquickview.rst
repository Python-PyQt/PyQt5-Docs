:orphan:

.. sip:class:: PyQt5.QtQuick.QQuickView
    :inherits: :sip:ref:`~PyQt5.QtQuick.QQuickWindow`
    :description: QtQuick/QQuickView-c.rst

    .. sip:enum:: PyQt5.QtQuick.QQuickView.ResizeMode
        :description: QtQuick/QQuickView-ResizeMode-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickView.ResizeMode.SizeRootObjectToView
            :description: QtQuick/QQuickView-ResizeMode-SizeRootObjectToView-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickView.ResizeMode.SizeViewToRootObject
            :description: QtQuick/QQuickView-ResizeMode-SizeViewToRootObject-v.rst

    .. sip:enum:: PyQt5.QtQuick.QQuickView.Status
        :description: QtQuick/QQuickView-Status-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickView.Status.Error
            :description: QtQuick/QQuickView-Status-Error-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickView.Status.Loading
            :description: QtQuick/QQuickView-Status-Loading-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickView.Status.Null
            :description: QtQuick/QQuickView-Status-Null-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QQuickView.Status.Ready
            :description: QtQuick/QQuickView-Status-Ready-v.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtGui.QWindow` = None
        :description: QtQuick/QQuickView-__init__-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.__init__
        :args:
            :sip:ref:`~PyQt5.QtQml.QQmlEngine`
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtQuick/QQuickView-__init__-f-1.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
            parent: :sip:ref:`~PyQt5.QtGui.QWindow` = None
        :description: QtQuick/QQuickView-__init__-f-2.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.engine
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlEngine`
        :description: QtQuick/QQuickView-engine-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.errors
        :returns:
            List[:sip:ref:`~PyQt5.QtQml.QQmlError`]
        :description: QtQuick/QQuickView-errors-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.initialSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtQuick/QQuickView-initialSize-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtQuick/QQuickView-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.keyReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtQuick/QQuickView-keyReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtQuick/QQuickView-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtQuick/QQuickView-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtQuick/QQuickView-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtQuick/QQuickView-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.resizeMode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QQuickView.ResizeMode`
        :description: QtQuick/QQuickView-resizeMode-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.rootContext
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlContext`
        :description: QtQuick/QQuickView-rootContext-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.rootObject
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QQuickItem`
        :description: QtQuick/QQuickView-rootObject-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.setInitialProperties
        :args:
            Dict[str, Any]
        :description: QtQuick/QQuickView-setInitialProperties-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.setResizeMode
        :args:
            :sip:ref:`~PyQt5.QtQuick.QQuickView.ResizeMode`
        :description: QtQuick/QQuickView-setResizeMode-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.setSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtQuick/QQuickView-setSource-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.source
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtQuick/QQuickView-source-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.status
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QQuickView.Status`
        :description: QtQuick/QQuickView-status-f.rst

    .. sip:method:: PyQt5.QtQuick.QQuickView.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtQuick/QQuickView-timerEvent-f.rst

    .. sip:signal:: PyQt5.QtQuick.QQuickView.statusChanged
        :args:
            :sip:ref:`~PyQt5.QtQuick.QQuickView.Status`
        :description: QtQuick/QQuickView-statusChanged-s.rst
